# dgStories - A Digital Story Book​

## Introduction

We live in a fast-paced, constantly changing world that revolves around technology. Life goes by in a blink of an eye, and our memories fade more and more each day. ​

However, we as humans have an urge to preserve our memories and tell our stories in the future. ​

Earlier, photo albums were the special items in our lives, especially because each album is filled with unique, individual photos that tell a story and reflect a moment we would like to remember. ​

With the times, technology has evolved, transforming all our physical items into a digital format.​

**dgStories** is an app that can help user conveniently author and preview stories to preserve memories and allow the user to relive the joyful moments of past, today and tomorrow.​

## User Story

Following are the user stories to be developed in the project:​

- As a user, I should be able to register with dgStories.​​
- As a user, I should be able to login with dgStories.​
- As a user, I should be able to create new story for authoring.​
- As a user, I should be able to author story with text, image and video components.​
- As a user, I should be able to style story components with color, font, position and order.​
- As a user, I should be able to edit and delete existing stories.​
- As a user, I should be able to preview existing stories in the reverse chronological order.​​

## Development Plan

Break down dgStories development process into milestones:​

1. Author User Story​
2. Preview User Story​

### Milestone 1: Author User Story​

- User should be allowed to create stories to capture and store the memories in multimedia format.​
- Stories will be designed on editable interface a.k.a canvas​.
- Stories will comprise of any of the following:​
    - Text​
    - Image​
    - Videos​
- The story will contain these components in stacked order.​
- User should be allowed to style the story components with colors and fonts.​
- The stories should be persisted for later access to preview, edit and delete.

### Milestone 2: Preview User Story​

- User should be allowed to view the persisted stories.​
- The stories should be displayed in reverse chronological order.​
- The stories should be listed in list format (stacked) one below the other or in the grid format based on user's choice.​​

### Instructions

1. Download and unzip the boilerplate code.  
2. Install the dependencies listed in `package.json` file. (Additional dependencies can be added as required)
3. Open the boilerplate code in VSCode to develop the assignment solution.  
4. Design documents should be saved in separate folder outside the source code.​
5. Solution should be developed using React library.​
6. Design principles like Single Responsibility Principle (SRP), and Do Not Repeat yourself (DRY) should be followed while building component hierarchy for single-page application, or SPA.​
7. Forms should be used to capture user inputs and should be adequately supported with validations.
8. Routes in SPA should be developed using library react-router-dom.​
9. Usage of MUI Library is suggested to implement Material Design while styling components​.
10. To write the test code for:​
    - Components use Jest framework​
    - Custom Hooks use react-hooks-testing-library​
11. As a backend support, json-server should be used with the data stored in .json file​.
12. Axios library can be used to make REST API calls to json-server for accessing data.​
13. Run the command `npm run lint` to test the code for hygiene checks.
14. Test the solution locally by running the command npm run test.  
15. Refactor the solution to ensure all unit and lint tests are passing.  
16. The solution code should contain the Readme.md file that provides the details that provides details for executing the project.​ The details should include:​
    - Project objective​
    - Tech stack used​
    - List of commands to run the:​
        - json-server ​
        - Application​
        - Test cases​
17. Zip the solution code with the name same as the assignment name.  
18. Upload the zipped solution for submission **without the node_modules files**.

## Evaluation Guidelines

1. The project will be tested based on hygiene checks.
2. The hygiene checks include:
    - Unused variables and functions should not exist.
    - React naming conventions should be followed for naming components.
    - Length of code lines should not be more than 90 characters.
    - String literals should be provided in double quotes.
    - External dependencies should not be directly referenced, instead should be installed as dependency of dev-dependency.
    - The code should comply to React conventions and declarations.
3. The hygiene checks are tested using ESLint tool.
4. The lint test results generated are stored in `eslint_html_report.html` file and are used to compute the score for grading the submission.
5. The graded score computation is dependent only on `errorCount`, `fatalErrorCount`, `warningCount` values and **Not On** `fixableErrorCount` and `fixableWarningCount` values.
6. These count values have varying weightage and has the following order of precedence (higher to lower): 
    1. FatalErrorCount
    2. ErrorCount
    3. WarningCount
