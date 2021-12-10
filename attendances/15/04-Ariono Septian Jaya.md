Ariono Septian Jaya
TI 3H

## CI/CD introduction

CI/CD is a method for frequently delivering applications to customers by introducing automation into the application development stage.
The "CI" in CI/CD always refers to continuous integration, which is an automation process for developers. Successful CI means new code changes to the application are regularly created, tested, and merged into a shared repository.
"CD" in CI/CD refers to continuous delivery and/or continuous deployment, which are related concepts that are sometimes used interchangeably.

## CI/CD Overview

In software development, several team members develop code and contribute to creating software functionality.
Two important aspects must be maintained to ensure codebase stability:
ensures that the code compiles without errors.
ensures that all unit tests that validate code behavior pass, including the most recent code changes, at a very high percentage.

## Introduction to GitHub Actions. GitHub is a set of actions in a GitHub repository workflow.

Action: The smallest building block of a workflow is an action that can be identified as an individual task.
Artifacts : Files generated when you build a software project or test your software project are artifacts.
Events: Events trigger workflows in GitHub Actions.

## GitHub Actions

GitHub-Hosted Runners: Hosted runners are similar to agents hosted on the Azure DevOps channel supported on Windows, Linux, and macOS.

Job: a step prepared for an individual consisting of one or more actions.

Self-Hosted Runner: useful when you have a specific hardware configuration for building a job application.

Step : Tasks that are commands are identified as steps.

Work : In GitHub repos, processes set up in YAML files that define build, test, package, or deployment tasks are called workflows.

Workflow Files: YAML files stored in the github/workflow/ folder in the GitHub repository.

Secrets and Tokens are important in any CI/CD pipeline implementation tool. Can protect sensitive information, such as connection strings and passwords, and store passwords or other secrets applied in application configuration settings.
Continuous Integration (CI) and Continuous Delivery (CD) use automation to ensure that new application code is always tested, secure, and ready to use so teams can deliver to production on time. CI is the process of testing and building software automatically after the new application code is integrated into a shared repository. While CD is the process of delivering applications made in the CI process to the production environment, which is entered through automated tests. Automated tests ensure that the application functions as expected when pushed into the production environment into the hands of real users.

Software is developed iteratively (iteratively) in small chunks based on frequent user feedback.
Tests are written during and implemented throughout the development process to ensure quality application code.
Security patches and bug fixes are quickly deployed through automation.
New application code is often integrated with the existing code base and tested to ensure the software is always ready for production.
Continuous Integration (CI) and Continuous Delivery (CD) use automation to ensure that new application code is always tested, secure, and ready to use so teams can deliver to production on time. CI is the process of testing and building software automatically after the new application code is integrated into a shared repository. While CD is the process of delivering applications made in the CI process to the production environment, which is entered through automated tests. Automated tests ensure that the application functions as expected when pushed into the production environment into the hands of real users.

Software is developed iteratively (iteratively) in small chunks based on frequent user feedback.
Tests are written during and implemented throughout the development process to ensure quality application code.
Security patches and bug fixes are quickly deployed through automation.
New application code is often integrated with the existing code base and tested to ensure the software is always ready for production.