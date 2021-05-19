# **Walmart Academy Stone 2 Statue (May 2021) Case Studies**
#### Source codes for Walmart Academy Stone 2 Statue (May 2021) case studies

---

## Project Structure

This repo is divided into 5 projects for the following case studies:
 - Case Study 1: folder name *cs-one*
 - Case Studies 2 & 3: folder name *cs-two-three*
 - Case Study 4: folder name *cs-four*
 - Case Study 5: folder name *cs-five-redux-app*
 - Case Study 6: ~~haven't got a chance to do it yet~~
 - Case Study 7: folder name *cs-seven*

---

## Init

All projects, except *cs-five-redux-app* were bootstraped using **create-react-app**. Command line for creating the react app (as an example for *cs-one*:

`npx create-react-app cs-one`

Project *cs-five-redux-app* was creating using the **redux template** for **create-react-app* (this actually uses the [**Redux Toolkit**](https://redux-toolkit.js.org/) `@reduxjs/toolkit`):

`npx create-react-app cs-five-redux-app --template redux`

---

## Packages

The projects require the following packages (check out the links to the project sites for docs and tutorials):
 - [react](https://reactjs.org/) 
 - [react-redux](https://react-redux.js.org/)
 - [@reduxjs/toolkit ](https://redux-toolkit.js.org/)
 - [react-router-dom ](https://reactrouter.com/web/guides/quick-start)
 - [react-icons](https://react-icons.github.io/react-icons/)
 - [jest](https://jestjs.io/)
 - [react-select](https://react-select.com/home)
 
### Auto install

To install the individual project dependencies, from the terminal go to the corresponding project folder and run:

`npm install`

### Manual install

In case, there are still any issue with packages after auto-installing the packages, here are the packages that need to be installed:

`npm install react react-redux @reduxjs/toolkit react-router-dom react-icons`

`npm install --save-dev jest`

*(using `--save-dev` since the unit testing is only applicable for dev)*

And, 

`npm install react-select` 

*(although I haven't really got a chance to make use of it)*

---

## Run

To run a project, from the terminal go to its folder and run:

`npm start`

To run jest all test scripts/suites in project *cs-seven*, from the terminal go to folder *cs-seven* and run:

`jest`

To run a specific test script/suite (e.g. `scriptLivenessCheck.test.js`), from the terminal go to folder *cs-seven* and run:
`jest scriptLivenessCheck.test.js`

---


*Feel free to clone this repo or if you have suggestions, fork and send me a PR.*

**ARKOPAL BHATTACHARYA** 2021
