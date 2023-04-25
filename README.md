# Exercise: List and keys

## Description:

Build a simple "Todo List" application using React components and props. You'll need to create two components to complete this exercise:

1. **TodoList**: This component will render a list of todo items. It should take one prop:
   - `todos`: An array of objects representing the todo items. Each todo item should have two properties:
     - `id`: A unique string identifier for the todo item.
     - `text`: A string representing the text of the todo item.
2. **App**: This component will render the `TodoList` component with some sample data.

## Here are the steps to complete this exercise:

1. Create a new file called `TodoList.tsx` and define the `TodoList` component.
2. Inside the `TodoList` component, render an unordered list (`<ul>`) with list items (`<li>`) for each todo item in the `todos` prop. Make sure to use a unique `key` prop for each list item.
3. Inside each list item, render the `text` property of the corresponding todo item.
4. Inside the `App` component, define a todos array with two todo items. Each todo item should have an `id` property (which should be a unique string) and a `text` property (which should be a string).
5. Render the `TodoList` component inside the `App` component, passing in the `todos` array as props.
6. Make sure that the todo items are displayed correctly.
