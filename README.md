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

	* [Database](README.md#database)

	* [Server](README.md#server)

	* [MISC](README.md#misc)

## Introduction

If you are reading this, it means that WebLaunch series have come to an end. The end of WebLaunch does not necessarily mean the end of your learning journey. In fact, it has just started.

Throughout WebLaunch, we had a lot of shortcomings, but one thing is for certain - we are passionate about technology and our goal is to spread it to as many people as possible. We are constantly improving and learning from the our past mistakes so that we can do even better in the future, for both ourselves, and for the community.

The end of WebLaunch does not mean the end of your learning journey. You might think that you are not a computing student, so there is no need for you to continue learning more advanced stuff. However, we believe that it is not just about having extra skillsets and knowledge under your belt, and to have an advantage when looking for a job. It also equips you with an important skill - to look at different problems from different perspectives. The ability to look at different perspectives when solving problems will definitely give you an edge in the future.

With all that in mind, we have decided to create this guide to provide you with some additional sources to further your learning journey, most of which we are unable to cover during our workshops due to time constraints.

This guide is seperated into 2 parts - [**Frontend**](README.md#frontend) and [**Backend**](README.md#backend).

## Frontend

Frontend means the part of a website or app that the user will interact with - the part most people will see.

### HTML & CSS

HTML and CSS are the most basic components in making a website. HTML defines the structure of the webpage, while CSS defines the appearance of the webpage. Although we have covered them both in WebLaunch, it is helpful to go through the tutorial again, to either refresh your memory, or to simply strengthen your understanding, and to look at the problems from a different perspective. They're also extremely helpful if you have friends that are interested in learning web development and web design but were not able to attend WebLaunch.

Do note that these tutorials are more advanced than what we have covered in WebLaunch. However, they are excellent resources as they provide plenty of examples for you to play with.

**Tutorial**

1. [FreeCodeCamp Tutorial](https://www.freecodecamp.org)

1. [W3Schools HTML Tutorial](https://www.w3schools.com/html/)

1. [W3Schools CSS Tutorial](https://www.w3schools.com/Css/)

### CSS Framework

#### What is a CSS framework?

A CSS framework is a framework in which all the CSS code that defines how different parts of a webpage should look has been writen by someone else (usually professionals) so that you do not need to rewrite everything by yourself. It allows you to create a website much faster as you simply need to copy them. Bulma, covered in Week 3 of WebLaunch, is an example of a CSS framework. You can check out the materials for that particular WebLaunch session [here](https://github.com/sunwaytechclub/2018-WebLaunch/tree/Bulma-completed)

#### Why use CSS frameworks?

1. Saves development time
1. Saves cost
1. No need to reinvent the wheel
1. They are many different styles and design languages to choose from

#### Examples of CSS frameworks

1. [Bulma](https://bulma.io/)

1. [Bootstrap](https://getbootstrap.com/)

1. [Foundation](https://foundation.zurb.com/)

1. [UIKit](https://getuikit.com/)

You don't have to know every single one of them, just pick one, and start using it. The best way to learn is through experimentation and reading the documentation. The documentation can be found easily in the website itself. It is usually called **Docs** or **Documentation**. Explore these CSS framework through their documentation and find out which parts of the framework you'll need. There is no best CSS framework, instead, each of them are suited for different situations and contexts.

### Static Site Generators

**What is a static site?**
A static site is a website that only displays information, and does not allow for any form of communication (sending and receiving data) from the user to the server (such as uploading images, logging in, etc). This website, for example, is a static site.

A Static Site Generator allows you to only worry about the content itself. You choose a theme, create the content of the webpage, and then the Static Site Generator will create the website for you, complete with the theme of your choice. Usually you will write your content in [Markdown](https://guides.github.com/features/mastering-markdown/).

If you so choose, you can also create your own templates, but that is a much more advanced topic. Some popular static site generators can be found [here](https://www.staticgen.com/). It includes links to each generators' official website, where you can find their documentation and start using them.

One popular Static Site Generator is [Jekyll](https://jekyllrb.com/). This very website was __made with Jekyll__.

### JavaScript

JavaScript was covered in the 4th and 5th Week of our workshops. The [first](https://github.com/sunwaytechclub/2018-WebLaunch/tree/JavaScript-completed) was the basics of JavaScript itself, while [latter](https://github.com/sunwaytechclub/2018-WebLaunch/tree/DOM) was ways to manipulate HTML and CSS using JavaScript. J

avaScript allows you to have extra functionality in your website. Apart from simply manipulating HTML and CSS directly (which is, in itself, an extremely powerful ability), you can also create complex interactive websites, such as games, webapps like Facebook and even Instagram (which was built with JavaScript). Unfortunately, we are unable to cover them in our workshops due to time constraints.

**Additional Javascript learning materials**

1. [Eloquent JavaScript Tutorial](https://eloquentjavascript.net/)

1. [Freecodecamp Tutorial](https://www.freecodecamp.org)

1. [Codecademy JavaScript Tutorial](https://www.codecademy.com/learn/introduction-to-javascript)

1. [W3Schools JavaScript Tutorial](https://www.w3schools.com/js/default.asp)


### API requests with AJAX

#### What is API?

API stands for Application Programming Interface. APIs are used to interact/interface with your website so that you can manipulate data and information. For example, how does your phone know what weather it is today? It uses an API to interact with a website (usually [weather.com](https://weather.com)), and allows it to collect revelant information from the website and display it on your phone.

**Example Scenario**

An example of a scenario which involves a `post` request for user to log into the website.

The code snippet below is an example of a `post` request, which will be sent to the API, and the server processing the request (information sent by your web browser) will collect the data you have entered (username and password) and will check with the database to see if your login details are correct.

```
[POST] https://www.sunwaytechclub.io/api/login
{
	"username": "sunwaytechclub",
	"password": "notGonnaTellYou"
}
```

If the details are correct, then a `success` response will be returned to your web browser, and along with it are `access tokens` and `refresh tokens`.

```
{
	"success": {
		"access_token": "dasdasdasdaskdjlkjlk",
		"refresh_token": "dasdasdjoijfiwjfowasf"
	}
}
```
**So what does it all mean?**

An [Access token](https://en.wikipedia.org/wiki/Access_token) is basically a string of data that is used for authentication (checking if your username and password are correct).

This might all seem very complicated and confusing, but worry not, because this is considered an advanced topic to learn. All you need to know from this is that with this type of authentication, the server will know that you had already signed in and who are you. With the access token, the server will limit you to information only you can see, so that you will not be able to access others' private data.

To sum it up, AJAX is a tool for you to communicate with your server and to ensure that the right access is given to the right people.

If you have already finished some JavaScript tutorials before reading this, you might have already come across API and AJAX. API and AJAX are extremely important if you want your website to do more than just being a static website.

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

## Backend

Backend is the part in a web where it does all the business logic and data persistent. Backend are usually made up of 2 component, which is databases and servers.

### Database

Database is an organized collection of data. It is a collection of schemes, tables, rows, etc. There are 2 type of database, which is SQL (Structured Query Language) database and NoSQL (Non Structured Query Language).

#### SQL

SQL is a language that enable CRUD (create, read, update, delete) on the data in a database.

Although SQL is an `ANSI/ISO` standard, there are different version of SQL language. However, the differences between each of them are very small. So, if you realize you are using one which is different from the one you had learnt, all you need to do is google and find out the differences (**VERY EASY**).

**Tutorial of SQL**

1. [W3Schools SQL Tutorial](https://www.w3schools.com/sql/sql_intro.asp)

1. [Codecademy Learn SQL](https://www.codecademy.com/learn/learn-sql)

**Examples of SQL databases**

1. [SQLite](https://sqlite.org/index.html)

1. [PostgreSQL](https://www.postgresql.org/)

1. [MariaDB](https://mariadb.com/)

1. [MySQL](https://www.mysql.com/)

#### NoSQL

NoSQL is basically a database used to manage huge sets of unstructured data, where they are not stored in tabular relations like relational databases. [More information for NoSQL database](https://www.studytonight.com/mongodb/what-is-nosql).

**Example of NoSQL database**

1. [MongoDB](https://www.mongodb.com/)

1. [Redis](https://redis.io/)

1. [CrouchDB](https://couchdb.apache.org/)

1. [RavenDB](https://ravendb.net/)

### Server

Server is a computer or computer program which manages access to a centralized resource or service in a network. When you press a button in a website, it send a request a server and wait for the response from the server. [Previously](README.md#api-requests-with-ajax) we had already discuss about API, server will be the one responsible for the API.

There are a wide range of languages (programming languages) can be choosen from to create a server. We will list out some common one and feel free to learn whichever one you are comfortable with.

Again, **YOU DO NOT NEED TO KNOW ALL** and documentation are included in their website.

#### Javascript

1. [Node.js](https://nodejs.org/en/docs/guides/)

1. [Feathers](https://docs.feathersjs.com/)

1. [Adonis](https://www.adonisjs.com/docs/4.1/installation)

#### Ruby

1. [Ruby on Rails](https://rubyonrails.org/)

#### Python

1. [Flask](http://flask.pocoo.org/)

1. [Django](https://www.djangoproject.com/)

1. [Pyramid](https://trypyramid.com/)

#### Java

1. [Spark Framework](http://sparkjava.com/)

1. [Play Framework](https://www.playframework.com/)

#### PHP

1. [Laravel](https://laravel.com/)

### MISC

Here are some of the concept which you might want to learn for backend

1. [RESTful](https://en.wikipedia.org/wiki/RESTful)

1. Authentication

	1. [JWT (JSON Web Token)](https://jwt.io/introduction/)

	1. [OAuth](https://oauth.net/2/)

1. Database

	1. [ORM](https://en.wikipedia.org/wiki/Object-relational_mapping)

		- [SQLAlchemy (Python)](http://docs.sqlalchemy.org/en/latest/index.html)

		- [Hibernate (Java)](http://hibernate.org/)

		- [Doctrine (PHP)](https://www.doctrine-project.org/)

		- [Propel (PHP)](http://propelorm.org/)

	1. [Schema Migration](https://en.wikipedia.org/wiki/Schema_migration)
