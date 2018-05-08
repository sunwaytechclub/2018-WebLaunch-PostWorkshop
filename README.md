# 2018-WebLaunch-PostWorkshop

## Table of contents

- [Introduction](README.md#introduction)

- [Frontend](README.md#frontend)

	* [HTML & CSS](README.md#html--css)

	* [CSS Framework](README.md#css-framework)

	* [Static Site Generator](README.md#static-site-generator)

	* [JavaScript](README.md#javascript)

	* [API requests with AJAX](README.md#api-requests-with-ajax)

	* [JavaScript Framework](README.md#javascript-framework)

- [Backend](README.md#backend)

## Introduction

If you are reading this, it mean that WebLaunch series had come to an end. The end of WebLaunch does not necessary mean the end of your learning journey, in fact it just started. 

Throughout the WebLaunch, we had a lot of shortcoming, we assume things, we went too fast, TA (teaching assistant) are not well prepared with the topic (I am one of them), we use jargon that difficult to understand, etc, but one thing that are certain is that we have a lot of passion. We are constantly trying to improve and learn from the past mistake so that we can do it even better in the future. 

The end of WebLaunch does not mean the end of your learning journey. You might think that you are not an IT student so there is no need for you to continue learning? In my opinion, it is not just about having an extra skills and have extra advantages in getting employed, it also equip you with skills looking at different perspective. Additional, this skills might help you in the future. 

We have decided to create this guide to provide you guys with some additional information that we are unable to cover during our workshops

This guide is seperated into 2 parts; [**Frontend**](README.md#frontend) and [**Backend**](README.md#backend).

## Frontend

As you had know, frontend is what you see in your website. 

### HTML & CSS

HTML and CSS is the most basic component in making a website. HTML defined how to structure looks like, while CSS defined the style or the appearance of the website. Although we had covered these in WebLaunch, but in case if you want to do some revision or you had friend who are interested but you do not have any resources, here are some tutorial which you can go through. 

**Tutorial**

1. [Freecodecamp Tutorial](https://www.freecodecamp.org)

1. [W3Schools HTML Tutorial](https://www.w3schools.com/html/)

1. [W3Schools CSS Tutorial](https://www.w3schools.com/Css/)

### CSS Framework

#### What is a CSS framework?

CSS framework is a framework where it include all the CSS code that had writen by some professional so that you do not need to rewrite it by yourself. It allow you to create a website much faster than you could had been without it. 

#### Why use CSS?

1. Save development time
1. Save cost
1. No need to reinvent the wheel (Unless for educational purpose)
1. Chances are, it is more beautiful than what you could come up with

#### Examples of CSS frameworks

1. [Bulma](https://bulma.io/)

1. [Bootstrap](https://getbootstrap.com/)

1. [Foundation](https://foundation.zurb.com/)

1. [UIKit](https://getuikit.com/)

1. Flexbox

Bulma is covered in our [third WebLaunch workshop](https://github.com/sunwaytechclub/2018-WebLaunch/tree/Bulma). There are many more CSS framework that we didn't have the time to cover. You can simply google **CSS Framework** to find out even more of them. 

You don't have to know every single one of them, just pick one, and master it. The best way to learn is through documentation. The documentation can be found easily in the website itself. It will usually call **Docs** or **Documentation**. Explore these CSS framework through the documentation and find out what suit you the most. There is no best CSS framework, but rather more suitable depending on the circumstances. 

### Static Site Generator

Static site generator allows you to only write the content and choose the theme that you want, and it will generate a static website for you. Usually you will write your content in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and it will generate a nice website for you. You can also create your own template if you didn't like the template.

Some of the example of static site generator can be found in [this website](https://www.staticgen.com/). 

In the website, it include a lot of different static site generator and they had include the official website for each of the framework, documentation can be found in their website too. 

Another notable mention is [Jekyll](https://jekyllrb.com/). The site that you are currently viewing right now is *made by Jekyll*.

### JavaScript

JavaScript is covered in our 4th and 5th workshop. One is purely [JavaScript](https://github.com/sunwaytechclub/2018-WebLaunch/tree/JavaScript), while the other are [DOM](https://github.com/sunwaytechclub/2018-WebLaunch/tree/DOM). JavaScript allow you to have extra functionality in your website. There are so much more to learn about Javascript, but we are unable to cover them all in our workshops due to time constraint.

**Additional Javascript learning materials**

1. [Eloquent JavaScript Tutorial](https://eloquentjavascript.net/)

1. [Freecodecamp Tutorial](https://www.freecodecamp.org)

1. [Codecademy JavaScript Tutorial](https://www.codecademy.com/learn/introduction-to-javascript)

1. [W3Schools JavaScript Tutorial](https://www.w3schools.com/js/default.asp)


### API requests with AJAX

#### What is API?

API is application programming interface. Just imagine you have a cloud server somewhere in China because renting server in China is cheap. Now imagine your server have a lot of your customer detail, include their username, password, name, phone number, etc and you making a website and you want to allow your customer to login and see their detail. So, how can it be done? 

Your server will have API, by sending requests from your frontend to the API, it will return you something. 

**Example**

Sample `post` requests for login

```
[POST] https://www.sunwaytechclub.io/api/login

{
	"username": "sunwaytechclub",
	"password": "notGonnaTellYou"
}
```

The above post requests will be send to a API endpoint which is `https://www.sunwaytechclub.io/api/login`, which from the url we can know that it is for login purposes, with the data include `username` and also `password`, and the server might return us something like this.

```
{
	"success": {
		"access_token": "dasdasdasdaskdjlkjlk",
		"refresh_token": "dasdasdjoijfiwjfowasf"
	}
}
```

[Access token](https://en.wikipedia.org/wiki/Access_token) is basically a token that use for [authentication](https://www.bu.edu/tech/about/security-resources/bestpractice/auth/) purposes. You might not understand what is it right now, but it is ok because it is a more advance topic. All you need to know is with this authentication, the server will know that you had already signed in and who are you. With the access token, you will able to see your own personal information but not your girlfriend and vice versa. 

To sum up everything, AJAX is a tool for you to communicate with your backend server, you can tell your backend server to login, to update your personal information, to delete a picture of yours, etc. 

If you had already finish some JavaScript tutorial before reading this, you might had already came across AJAX, but I make a dedication section for AJAX is because it is extra important if you want your website to not just a static website but can also do a lot of things. 

**Additional AJAX learning materials**

1. [Freecodecamp Tutorial](https://www.freecodecamp.org)

1. [Codecademy Requests Tutorial](https://www.codecademy.com/courses/intermediate-javascript-requests/lessons/requests-i/exercises/requests-intro-i?course_redirect=introduction-to-javascript)

1. [W3Schools AJAX Tutorial](https://www.w3schools.com/js/js_ajax_intro.asp)

### JavaScript Framework

What is a JavaScript framework and why do you need one? From [Wikipedia](https://en.wikipedia.org/wiki/JavaScript_framework), the definition of JavaScript framework is 

>
A JavaScript framework is an application framework written in JavaScript. 
It differs from a JavaScript library in its control flow: [1] A library offers functions to be called by its parent code, whereas a framework defines the entire application design. [2] A developer does not call a framework; instead it is the framework that will call and use the code in some particular way. Some JavaScript frameworks follow the model–view–controller paradigm designed to segregate a web application into orthogonal units to improve code quality and maintainability.

Basically JavaScript framework is a framework that allow you to run JavaScript in your own computer like any other application do, not just live inside the browser. With JavaScript framework, you can now do a lot more things. More on that will be covered in [backend](README.md#backend). 

For a small project, you might find JavaScript framework very overwhelming and exhausting, however it is better when doing a big scale project because it has a certain way of doing things, hence increase the code quality and maintainability. It make things more structured for us to understand. 

Just like CSS Framework, we will list out some popular JavaScript framework, and feel free to learn anyone that you like, each has their own advantages and disadvantages, and **YOU DO NOT NEED TO KNOW EVERY SINGLE ONE OF THEM**. 

All of these framework will include documentation either within their website or a dedicated documentation for the framework, and that is how most of us learn a JavaScript framework. Of course, you might find some of the JavaScript tutorial above actually include tutorial for JavaScript framework, but it is most likely to be either `Node.js` or `React` because these 2 are relatively more popular than others and there are `A HELL LOT OF JAVASCRIPT FRAMEWORK`.

**JavaScript framework**

1. [React](https://reactjs.org/)

1. [Node.js](https://nodejs.org/en/docs/guides/)

1. [Angular](https://docs.angularjs.org/tutorial)

1. [Vue.js](https://v1.vuejs.org/guide/installation.html)

1. [Nuxt.js](https://nuxtjs.org/guide)

1. [Feathers](https://docs.feathersjs.com/)

1. [Adonis](https://www.adonisjs.com/docs/4.1/installation)

## Backend

Backend is the part in a web where it does all the business logic and data persistent. 