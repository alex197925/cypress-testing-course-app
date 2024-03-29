# Real World Testing with Cypress - Course App

This application is for the [Testing your first application course](https://learn.cypress.io/testing-your-first-application) on [learn.cypress.io](https://learn.cypress.io/).

The `start` branch is the main branch for this repo and is the starting point for the course. The [final](https://github.com/cypress-io/cypress-realworld-testing-course-app/tree/final) branch contains the completed tests.

# Cypress Framework Learning Journey

## Welcome to my  journey into mastering the Cypress automation testing framework! 

  Comprehensive guide:
  
  **Installation**

  >1. Install Cypress via npm:
  ```
npm install cypress --save-dev
  ```
  >2. Open Cypress:
  ````
npx cypress open

````
> ### This command launches the Cypress Test Runner, allowing you to manage and run your tests seamlessly.

## Testing text with Cypress
###  Example:
```
 context("hero section", () => {
    it("the h1 contains the correct text", () => {
      cy.get("h1")
        .should("exist")
        .contains("Testing Next.js Applications with Cypress")
    })
```




