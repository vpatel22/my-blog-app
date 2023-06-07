# A Basic Blog Application

This project is a full stack web application leveraging React, Express, MongoDB and Firebase Authentication. It contains basic login and logout functionality. Logged in users can then upvote and comment on each of the listed articles (currently just junk).

## Some additional details

Right now all articles are visible upon page load - however, the upvote and comment functionality only works for logged in users. User login functionality is backed by Google's Firebase Authentication and just uses email and password.

The upvote and comment functionality is very basic - a user can upvote an article once but cannot remove an upvote. There is also no downvote option right now. Comments cannot be edited or removed.

New ideas/issues are currently listed in a [Github Project](https://github.com/users/vpatel22/projects/2) and will be worked on eventually!

## Background context

This project is heavily based off of the [React: Creating and Hosting a Full-Stack Site](https://www.linkedin.com/learning/react-creating-and-hosting-a-full-stack-site-15153869?contextUrn=urn%3Ali%3AlyndaLearningPath%3A593715e0498e9e9be7fb8506&u=103733490) LinkedIn Learning course by Shaun Wassell. Feel free to take a look at the [Github Repo](https://github.com/LinkedInLearning/react-creating-and-hosting-a-full-stack-site-3209140) for that project as well.

This project started with the base [Create React App](https://github.com/facebook/create-react-app) application and was heavily modified from that point.

## Differences between this and the LinkedIn project

Currently, there are no large differences in how this application looks and functions vs the one that exists for the course. This will change eventually once some of the ideas in the project are implemented.

## Running this application locally (WIP, not fully available yet)

You will need to clone to repos to run this project locally, as this repo only contains the back-end for the project (the */build* folder containing the front-end components were not committed). The FE repo can be found [here](). To run this project:

1. Run `npm install`
2. Set up mongodb locally using the instructions 
```
npm run dev
```

This will install the dependencies in the [`package.json`](/my-blog-backend/package.json) file and then open port 8000 to listen for requests. You should only need to use [http://localhost:8000](http://localhost:8000) if you wish to test the server through something like Postman.