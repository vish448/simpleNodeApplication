# SimpleNodeApplication With Git and Heroku
This repo will show how to create node application and process with automatic deployment with Heorku bridging with Git.

## What you need
Github repository
Heroku free account

## How
I believe you have npm installed in your local machine.

Create a new node project from terminal in your local machine.
-cd project folder
-node init

It will allow you to create package.json

Create app.js which will output H1 tag in the browser

Commit your changes to git by pusing local changes to the git repository

## Deployment with HerokuApp
-Create a free account with Heroku
-Create an app with your account
-With Deployment method choose GitHub and allow access to Heroku to connect withyour git repository
-Search for your repository and press connect
-Select the branch 'master' and press the 'Enable Automatic Deploys'
-Now we need to tell heroku which application we are deploying
--Go to Settings tab and locate Buildpacks and click 'Add buildpack'
--Choose 'nodejs' and save changes.
-Now go back to Deploy tab and click Deploy Branch at the bottom

So now everytime you start pushing to git will deploy your changes directly to heroku.

