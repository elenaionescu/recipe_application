# The Challenge

There is a request for a new food / recipe application that will help users become 
better at cooking. Unfortunately the product manager has dumped a bunch of specifications 
on you and done a runner!

Your task is to develop an application that fulfils _some_ or _all_ 
of the specification provided.

## What are we looking for?
The aim of the task is to give you the opportunity to show **your** skills in web development. The specification is deliberately open for that reason. If you aren't strong in front-end development or you haven't done much server-side development, don't worry... **Play to your strengths!**

We are also very interested in _non-coding_ aspects and how you approach problems. 
Please supply any notes you make, such as showing your working, questions you might want to ask and assumptions you may have made.
We also **strongly** recommend you use comments in any code you supply to communicate your reasoning as you work.

The languages that will be accepted are:

• JavaScript
• Node.js
• React.js

The `features` folder contains the behavioural specifications of the application to be built. Start by reading through these feature files, 
they should give you a sense of what is required.

MyRecipes uses the following tools:

* Yeoman to manage the tech stack
* Node.js for the back-end
* Express to link the back-end and the database
* MongoDB for the database
* AngularJS to render a fluid AJAX front-end
* Bootstrap to render a responsive and cross-browser website
The front-end is communicating with the back-end through a REST API.work.

## Features

- Feature: Recipe
    * Scenario: Recipe doesn't exist
    * Scenario: Recipe cooking time
    * Scenario: Recipe image
    * Scenario: Recipe ingredients
- Feature: Recipe list
    * Scenario: No recipes available
    * Scenario: One recipe available
    * Scenario: Select a recipe
    * Scenario: Multiple recipes
    * Scenario: Multiple pages of recipes
    * Scenario: Navigating multiple pages of recipes
- Feature: Filter recipes
    * Scenario: No results
    * Scenario: Filter results by name
    * Scenario: Filter results by ingredient
    * Scenario: Filter by cooking time
- Feature: Star
    * Scenario: Star a recipe
    * Scenario: Unstar a recipe
    * Scenario: No starred recipes
    * Scenario: Show only starred recipes

## Development

Requirements:

First, make sure you have a MongoDB instance on your machine, then:

`sudo npm install -g grunt-cli
sudo npm install -g npm
sudo npm install -g generator-angular-fullstack
sudo npm install -g bower
sudo npm install -g yo`

To launch:

`grunt serve`

## Where to start

The `features` folder contains the behavioural specifications of the
application to be built. Start by reading through these feature files,
they should give you a sense of what is required. Remember, you don't 
_have_ to satisfy them all!
