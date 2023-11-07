# Pizza Ordering Web App

![PizzaMenu](https://github.com/guilhermeSilva96/PizzaMenu/assets/139381851/d613fa3f-ecf1-4e78-ae33-75ed0099ef9e)


This is a simple web application for a pizza restaurant, built using React. In this README, we'll explore the JavaScript mechanics and fundamentals used in the code.

## JavaScript Mechanics and Fundamentals

1. **Data Array (pizzaData):** The `pizzaData` array stores information about different pizza menu items. It includes details like the pizza name, ingredients, price, photo name, and whether it's sold out or not. This is a fundamental concept of working with structured data.

2. **React Components:** The application is structured using React components, including `App`, `Header`, `Menu`, `Pizza`, and `Footer`. This showcases the use of component-based architecture in building web applications.

3. **Conditional Rendering:** The code uses conditional rendering to display different content based on conditions. For example, it checks if there are pizzas in the menu and conditionally renders either the menu or a "work in progress" message.

4. **Props:** The `Pizza` component receives `pizzaObj` as a prop to display pizza details. This demonstrates the passing of data from parent to child components using props.

5. **Dynamic Styling:** The `sold-out` class is conditionally applied to a pizza's list item based on its availability, showcasing dynamic styling using CSS classes.

6. **Date and Time Handling:** The `Footer` component determines whether the restaurant is open based on the current time. This involves handling date and time using JavaScript's `Date` object.

7. **React Roots:** The code uses `ReactDom.createRoot` to render the `App` component into the root DOM element. This is part of React's rendering process.

8. **ES6 Features:** The code employs various ES6 features such as arrow functions, template literals, and destructuring assignment.

## Getting Started

To run this application locally, you need to have Node.js and npm (Node Package Manager) installed. Follow these steps:

1. Clone the repository to your local machine.

2. Navigate to the project directory in your terminal.

3. Run the following commands:
   - npm install
   - npm start
  
4. The application will be available at `http://localhost:3000` in your web browser.
