---
layout: post
title: "React-Redux-Flask, A Modern Web Application Boilerplate"
published: true
---


----

This blog post talks about my web application boilerplate found <a target="_blank" href="https://github.com/dternyak/React-Redux-Flask">here</a>.
-----
<hr>

A modern web application is going to have a back-end and front-end.

Sometimes the back-end will be a BaaS (back-end as a service) like Firebase, but most people will write their own custom backend. Flask is a popular option if you're using python.

Now, for the front-end, there are two options.
One is a back-end rendered template, which Jinja2 is a good option for. The other is to use a SPA (single-page application). These websites are dynamic and respond to the user without reloading. 


React is a popular choice for building SPA's, but it requires putting together a lot of other microlibraries to get everything working smoothly (for example, you need a library like redux to store data, and a library like react-redux-router to handle the front-end routing).

React-Redux-Flask is a sample application that has everything setup for you so you can get to building the app itself.

It includes:

- Restricted Routes in React (authenticated via JWT)
- Babel 6
- React-Router-Redux
- React Router 2.0
- SCSS processing
- Webpack
