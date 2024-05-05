## <h1 align="center" style="font-weight: bold;">Budget-App</h1>

<p align="center">
<a href="#features">Features</a>
<a href="#skeleton">Project Skeleton</a>
<a href="#usage">Usage</a>
<a href="#technologies">Technologies</a> 
</p>

<p align="center">
<a href="https://ibm-budget-app-becoo.netlify.app/">📱 Visit this Project</a>
</p>

## IBM React Final Project Budgeting Allocation Application
- This project is a budget allocation application developed using React.js. It allows users to allocate budgets to different departments, track expenses, and manage their budget effectively.
## <h2 id="features">🤖Features:</h2>
- Budget Allocation: Users can allocate budgets to various departments such as Marketing, Sales, Finance, HR, IT, and Admin.
- Expense Tracking: Users can track expenses for each department and monitor their spending.
- Budget Management: Users can dynamically adjust the budget, add or reduce allocations, and see the remaining budget.
- Currency Selection: Users can choose their preferred currency from options including Dollar, Pound, Euro, and Rupee.

## <h2 id="skeleton">Project Skeleton</h2>

```
Budget-App(folder)
|
|----readme.md    
SOLUTION
├── public
│     ├── index.html
│     ├── favicon.ico
│     ├── logo192.png
│     ├── logo512.png
│     ├── manifest.json
│     └── robots.txt
├── src
│   ├── App.js
│   ├── App.css
│   ├── components
│   │   ├── AllocationForm.js
│   │   ├── Budget.js
│   │   ├── Currency.js
│   │   ├── ExpenseItem.js
│   │   ├── ExpenseList.js
│   │   ├── ExpenseTotal.js
│   │   └── Remaining.js
│   ├── index.css
│   ├── index.js
│   ├── context
│       └── AppContext.js
├── package.json
└── yarn.lock
```


## <h2 id="usage">🔍Usage</h2>
- Once the application is running, you can access it via your web browser. Here are the main functionalities:

- Budget Allocation: Select a department from the dropdown menu, choose an action (Add or Reduce), enter the allocation amount, and click "Save" to allocate the budget.
- Expense Tracking: View the list of departments and their allocated budgets, along with options to increase, decrease, or delete expenses.
- Budget Management: Adjust the total budget by entering a new value in the input field and pressing Enter.
- Currency Selection: Click on the currency button to open the currency menu, then select your preferred currency.

## <h2 id="technologies">🛠️Technologies I Used</h2>
- React.js
- Boostrap
- react-redux
- redux
