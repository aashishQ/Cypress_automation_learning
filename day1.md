What is Cypress?
------------------
It is Frontend web automation testing tool where" we can automate testing on the browser

--> Cypress support only JavaScript and use mocaframework
--> Node.js and comes with npm module

Syntax:
----------
it("This is the testcase heading)" function (){
// test case goes here

});

OR,

it("This is the testcase heading" () =>{
    // test case goes here
})

What we can do?
---------------
--> End to End testing
--> Integratin Testing
--> Unit Testing   (Mostly developers)
--> API testing


Selenium vs Cypress?
---------------------
Only Web || web and API

Open Source || Test Runner is free while Dashboard is paid

Setup is Difficult || Setup is easy

LAnguage: Java, Python, Ruby, C#, JS  || JS and TypeScript

Browser: Chrome,Edge,Firefox,safari,Opera & IE || Chrome, Edge, Firefox, Electron

Framework: Junit, TestNG,PyTest || Mocha JS

Performance: slow (outside of browser) || faster (inside browser)

Reporting: integrate with Extent and Alure || Mocha reportes and Cypress Dashboard


Cypress Eco System
-------------------
1. TestRunner -- open source, locally installed
2. Dashboard -- paid


Main Feature:
--------------
a. Time travel - for everyline cypress screnshots everything
b. Debugging - Access of devtools
c. Automating waits (built-in waits/default waiting time): solves synchronization problem
d. consistent results
e. screnshots and videos (inbuilt)
f. cross browser testing (locally or remotely)

Limitations:
--------------
a. cannot automate automation windo based / Mobile apps
b. Limited browser supports
c. Only JS or TS is only supported
d. r/w into files is difficult
e. reporting only Dashboard or Mocha reports 

visit the officail website of the selenium:
https://docs.cypress.io/guides/overview/why-cypress

Pre Requisit To Learn Cypress
------------------------------
Language --> Javascript
Framework --> MOCHA || JS Test Framework with Chai, Chai-JQuery abd Sinon
Assertion --> CHAI, SINON & CHAI-JQUERY
Element Locator --> CSS
                --> JQUERY 
                --> XPATH || install plugin to use xpath 
Element Method --> JQUERY
REPORT --> MOCHAWESOME
NODE Basics --> Node Basic
WEB & API Concepts

Installing Cypress
------------------
-> Download NODE
--> Download editor
--> create a folder for cypress
--> run " npm init -y" in the folder
--> run "npm i cypress"
--> run in editor
--> In package.JSON - ADD SCRIPT - "test":"cypress open"
--> in terminal "npm test"
--> check cypress folder