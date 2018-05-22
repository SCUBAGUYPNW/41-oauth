![cf](http://i.imgur.com/7v5ASc8.png) 41: OAuth
===

## Submission Instructions
  * Work in a fork of this repository
  * Work in a branch on your fork
  * Write all of your code in a directory named `lab-` + `<your name>` **e.g.** `lab-duncan`
  * Submit a pull request to this repository
  * Submit a link to your pull request on canvas
  * Submit a question, observation, and how long you spent on canvas 
  
## Learning Objectives  
* Students will learn to add Google OAuth to an express/mongo app

## Requirements  
Create a full-stack app that allows users to authenticate
with OAuth via Google.

#### Configuration  
* create a `/lab-<yourname>/backend` directory
* create a `/lab-<yourname>/frontend` directory

#### Feature Tasks  

#### backend
* create an app on the google dev console
 * configure oauth credentials to support a client app on `http://localhost`
 * configure oauth credentials to support a server redirect uri to `http://localhost:3000/oauth/google/code`
* create a backend route `GET /oauth/google/code` for handling google oauth 

#### frontend 
* create an index.html with an anchor tag pointing to the google authorization page 
* configure the query string with correct key value pairs

#### Documentation  
Write a description of the project in your README.md, including detailed instructions for how to build your app. In your frontend README.md add a code block with your frontend .env vars, and in your backend README.md add a code block with your backend .env vars. 
