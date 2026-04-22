# Syncfusion DataGrid with Jest Test Case on Vue

## Repository Description

This repository contains a Vue.js sample application that demonstrates how to write and execute Jest unit test cases for a Syncfusion Vue DataGrid component.

## Project Overview

This sample showcases how to integrate Jest testing into a Vue application that uses the Syncfusion Vue DataGrid. Unit testing is an important practice for validating individual components and ensuring application stability. In this project, Jest is used along with Vue Test Utils to test the behavior of a Syncfusion DataGrid rendered inside a Vue component.

The application renders a DataGrid bound to a local data source and includes a unit test that verifies the number of records bound to the grid. This approach helps developers validate component behavior early in the development cycle and catch potential issues before deployment.

## Key Features

- Syncfusion Vue DataGrid integration
- Jest-based unit testing setup for Vue components
- Validation of grid data binding through test cases
- Lightweight sample focused on testing fundamentals

## Node Version Requirement

Verify that the installed Node.js version is 14 or higher. If the installed version is below 14, install a newer version from the official Node.js website:
<https://nodejs.org/en/download>

## Running and Testing the Application

Follow the steps below to install dependencies, run the application, and execute unit tests.

1. Install the required npm packages:

   ```bash
   npm install
   ```

2. Run the application locally for development or manual verification:

   ```bash
   npm run serve
   ```

   Once the development server starts, open the displayed local URL in a browser to view the Syncfusion DataGrid.

3. Execute the Jest unit test cases:

   ```bash
   npm run test
   ```

    The test validates that the DataGrid is rendered with the expected number of records based on the bound data source.

## Additional Resources

- [Vue Testing Documentation](https://vuejs.org/guide/scaling-up/testing)
- [Jest Documentation](https://jestjs.io/docs/getting-started)
- [Syncfusion Vue Grid Documentation](https://ej2.syncfusion.com/vue/documentation/grid/getting-started)
- [Syncfusion Vue Grid Demos](https://ej2.syncfusion.com/vue/demos)
