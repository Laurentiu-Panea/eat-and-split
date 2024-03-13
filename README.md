This project is a React application designed to manage shared expenses among friends. It allows users to add friends, track balances, and split bills efficiently. The main features include:

Friends List: Displays a list of friends with their names, profile pictures, and balances. Users can select a friend to split bills with.
Add Friend: Users can add new friends by providing their names and profile picture URLs.
Split Bill: Enables users to split bills with selected friends. Users input the total bill amount and their own expenses. The application calculates the amount owed or owed to each party accordingly.
Delete Friend: Allows users to remove a friend from the list, along with their associated expenses.

Technical Description
This React application is built with modern web development technologies and follows best practices in React development. Here's an overview of the techniques and technologies used:

React  : The project is developed using React, a popular JavaScript library for building user interfaces. React's component-based architecture facilitates the organization and management of UI elements.

React Hooks  : Utilizes React Hooks such as useState for managing state within functional components. This allows for stateful logic without using class components.

Functional Components  : The project predominantly employs functional components instead of class components. Functional components are simpler and provide better readability and maintainability.

State Management  : State management is handled using React's useState hook. It maintains the state of friends, showing/hiding add friend form, selected friend, and bill splitting information.

Conditional Rendering  : Implements conditional rendering to display or hide UI elements based on certain conditions. For example, showing the add friend form or bill splitting form based on user interaction.

Event Handling  : Utilizes event handling to manage user interactions. Functions like handleShowAddFriend, handleAddFriend, handleSelectedFriend, and handleSplitBill manage various user actions like adding friends, selecting friends, and splitting bills.

Forms  : Implements forms for user input using standard HTML form elements. Data from these forms is captured using React state and processed accordingly.

CSS  : The styling is done using CSS. Classes like .app, .sidebar, .button, .form-add-friend, and .form-split-bill are defined to style different components of the application.

ES6 Features  : Employs ES6 features like arrow functions, destructuring, template literals, and let/const declarations for cleaner and more concise code.

This project demonstrates proficiency in React development, including state management, event handling, and component composition. It also reflects familiarity with modern JavaScript and best practices in web development.


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
