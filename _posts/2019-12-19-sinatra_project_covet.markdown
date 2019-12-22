---
layout: post
title:      "Sinatra Project: Covet"
date:       2019-12-19 10:06:14 -0500
permalink:  sinatra_project_covet
---



For my second Flatiron School assessment, I wanted think like an aspiring product manager and to try to solve a real-life "problem" for the theatre, based on my own experiences as a Broadway fan. I have a lot of merchandise and collectibles and I like to keep track of my stuff. I have seen many other fans who post videos of their hauls of merchandise. 

I decided to create a Sinatra app called "Covet." Sinatra is a Ruby gem that allows you to specify how an app will respond to different http requests (GET, POST, etc.) and routes. 

As per the requirements of the project, the web app should allow users to create, read, update and delete (CRUD) resources. In addition, the project uses basic Model/View/Controller architecture. It has a few simple models that interact with various routes (the part of the URL after the domain) in the controller which then composes and serves the different pages through the views.

To get organized I created a list of items by category so I could figure out how to set up my views and create the file structure and environment. As required by the project, we also need to be able to login and logout of the app. I envisioned that once a user signs up on the website, the fan is able to view other users' inventories and has the ability to create a an inventory of their own stuff. 

I tested out this application in the browser with the help of a gem called Shotgun, which allows you to refresh a page to see changes, no need to restart the local server.

To use this app, just clone, run rake db:migrate and then run shotgun.

The repo for this app can be found at: git@github.com:mitzvahgirl/Covet.git


