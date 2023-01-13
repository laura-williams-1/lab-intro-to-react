# React Introduction Lab

Edit multiple JavaScript files in this lab as you get the hang of creating and using components.

---

## Lab Setup

### Getting started

1. Fork and clone this repository.

1. Navigate to the cloned repository's directory on your command line. Then, run the following command:

   ```
   npm install
   ```

   This will install the libraries needed to run the tests.

1. Open up the repository in VSCode. Follow the instructions below to complete the Lab.

### Tests

> **Note**: Do not agree to any updates or changes to configurations when booting up Cypress. Cypress is already configured for you. If you agree to updates, you will need to make additional changes to the testing files, rather than being able to work on your lab.

To run the tests, you can run the following command from the command line. You will need to be in the root directory of your local directory.

```
npm test
```

This will open the Cypress testing window, where you can click to run an individual suite of tests or all of the tests at once.

#### Testing Tips

Keep the following in mind for this lab as you run the tests.

1. The application mockups below are a design reference for if you have time. The main purpose of this lab is to connect all the components and get the tests to pass.

1. While running your tests, you must have a server up and running in another terminal. This means you will have _both_ a terminal window running the actual React application _and_ a terminal window running the tests.

1. When creating a component, make sure to create and import it with the same name as the file name. For example, the component created and exported inside of the `Post.js` file should be `Post`. The tests look for these specific names.

1. While the `cypress-watch-and-reload` package has been installed in this project, sometimes the React application will take longer to reload than the tests. If you feel as though a test should be passing that isn't, try pressing the re-run button in the Cypress tests before asking for help.

## Instructions

You will be building a static React Application that will show some blog posts and user information. It should look similar to the image below. Note: this view has been lightly styled to help provide clarity between components, you do not need to style this app the same way.

![ProfilePage](./ProfilePage.png)

Rather than building on large HTML file, you will break up this view into multiple React components. You will create each component in its own file, export it, then import it into `App.js`, then you will structure the components to match the hierarchy listed below.

You are given a number of blank files inside of `src/Components`, which will help guide you in figuring out what components you will need, along with the unit tests.

Connect all of the components inside of the `Components/` directory so that each component shows up on the page.

Your application should have the following component structure:

![components tree](./component_tree.png)

The component tree above can also be shown as a list:

![components list](./components.png)

If you have time, build out the page to be more detailed and styled, like the following mockup image.

![ProfilePage](./ProfilePage.png)
