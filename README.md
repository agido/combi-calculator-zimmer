# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


## Task
### Idea

A simple form with which you can calculate a combination bet (parlay). See example from https://www.covers.com/tools/parlay-calculator

### Requirements

The Parlay calculator should be displayed as a form. The calculator should work completely independently in the browser. The form is structured as follows:

- A dropdown where you can select the odds format. Options are "Decimal", "Fractional" and "American" with "Decimal" as default.
- An input for the first odd. Label for the Input "First Odd" or "Odd 1". A small button with a question mark next to the label. When you click on this button, an overlay appears with an explanation of how to fill in the input correctly.
- An input for the second odd. Label for the Input "Second Odd" or "Odd 2".
- A button with which you can create an additional input. For this additional Input the Label is "Third Odd" or "Odd 3". All subsequent inputs follow this pattern.
- An input for the stake. Label for this input "Stake/ Wager Amount". Next to the Label is a button with a questionmark in it. When you click on this button, an overlay appears with an explanation of how to fill in the input correctly. e.g. "Enter the amount of money you plan to wager."
- An area in which the result of the calculations is displayed. Label is "Total Payout". next to the label is again a Helpbutton (with a questionmark) which opens an overlay with the text "This is the amount you will receive if you win your bet (original wager amount plus profit)."
- A Button to calculate the combined Odds. When you hit the Button all odds from the inputs and from the stake input are multiplied together and then output or displayed in the result area.
- A Button to Reset the whole form. Clicking will clear all inputs and reset the Odds format dropdown to default.


## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
