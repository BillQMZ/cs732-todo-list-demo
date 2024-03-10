# CS732/SE750 Demo - My Todo List

This project will contain a complete full-stack todo list app, using the MERN stack (MongoDB, Express, React, Node.js). The project is divided into [frontend](./frontend/) and [backend](./backend/) sub-folders.

Each video in the tutorial series will be associated with a `git` branch, containing the end-point of that video. The branches are as follows:

## Branches

1. **main:** The starting point for the project. The frontend is a stripped-down version of the starter React project created using `npm create vite@latest`. The backend is a barebones Node.js "Hello World" app with the reommended folder structure, but no content.

2. **step-1-displaying-todos:** In this step, we create some dummy data using ChatGPT, and then create a `<ul>` in `App.jsx`to display todo items in a list. We use JavaScript arrays' `map()` function to dynamically render a `<li>` for each todo item.

3. **step-2-react-components:** In this step, we refactor our initial todo list to use two _React components_:

   - `TodoList`: Is responsible for displaying a list of todo items.

   - `TodoListItem`: Is responsible for displaying a single todo item.

4. **step-3-dayjs:** In this step, we use the `dayjs` _npm package_ to help us display our todo items' due dates in a more user-friendly way. We also use it to calculate whether a todo item is _overdue_ (i.e. its due date is in the past), and display a todo item's status of either "Complete", "Pending" (incomplete but with a due date still in the future), or "Overdue" (incomplete with a due date in the past).

5. **step-4-styling-1:** In this step, we create two _CSS modules_ - one for `App.jsx` and one for `TodoList.jsx`. We add some styes to these modules to make our todo list look a little prettier.

6. **step-5-styling-2:** In this step, we complete the styling of todo items by making their status buttons change color depending on the status.

7. **step-6-completing-deleting:** In this step, we show how to use `useState()` to create a _stateful_ value in React. We also show how we can _propagate_ events - such as button clicks - up the component hierarchy using event props. Finally, we show how we can appropriately call the stateful value's _setter_ function to modify and remove todo items.
