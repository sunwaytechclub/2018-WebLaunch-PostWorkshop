# 2018-WebLaunch-PostWorkshop

## Table of contents

- [Introduction](README.md#introduction)

- [Guide](README.md#guide)

	* [Frontend](README.md#frontend)

		- [HTML & CSS](README.md#html--css)

		- [CSS Framework](README.md#css-framework)

		- [Static Site Generator](README.md#static-site-generator)

		- [JavaScript](README.md#javascript)

		- [API requests with AJAX](README.md#api-requests-with-ajax)

		- [JavaScript Framework](README.md#javascript-framework)

	* [Backend](README.md#backend)

## Introduction

If you are reading this, it mean that WebLaunch series had come to an end. The end of WebLaunch does not necessary mean the end of your learning journey, in fact it just started. 

Throughout the WebLaunch, we had a lot of shortcoming, we assume things, we went too fast, ta (teaching assistant) are not well prepared with the topic (I am one of them), we use jargon that difficult to understand, etc, but one thing that are certain is that we have a lot of passion. We are constantly trying to improve and learn from the past mistake so that we can do it even better in the future. 

As I mention earlier, end of WebLaunch does not mean the end of your journey. You might think that you are just a business student, or others, why do you need to continue learning web development? In my personal opinion, it is not really about having a special skills so it is easier to get employed, or you learn it because you are an IT student so that you can earn a lot of money being a web developer, but it is more about self enhancement. You might be a business student, finance student, marketing student, etc, but it does not mean that you only can learn about what you specialize in. I am an computer science student does not mean that I cannot learn economics, finance, psychology, philosophy, etc on my own. Equip yourself with more skills allow you to look at things with more perspective, and this skills might also help you in the future. 

Throughout the whole workshop, we had covered topic which includes **HTML**, **CSS**, **Bulma**, **JavaScript** and **DOM**. With these knowledge, it is sufficient to create a static website. But what is a static website? A static website is basically a website that cannot do things like login, chat, etc. But how can you achieve it? 

In this guide, there will be seperated into 2 part, which is Frontend and Backend. What we had learnt so far are all within the scope of frontend. 

## Guide

### Frontend

As you had know, frontend is what you see in your website. 

#### HTML & CSS

HTML and CSS is the most basic component in making a website. HTML defined how to structure looks like, while CSS defined the style or the appearance of the website. Although we had covered these in WebLaunch, but in case if you want to do some revision or you had friend who are interested but you do not have any resources, here are some tutorial which you can go through. 

**Tutorial**

1. [Freecodecamp Tutorial](https://www.freecodecamp.org)

1. [W3Schools HTML Tutorial](https://www.w3schools.com/html/)

1. [W3Schools CSS Tutorial](https://www.w3schools.com/Css/)

#### CSS Framework

What is CSS framework? CSS framework is a framework where it include all the CSS code that had writen by some professional so that you do not need to rewrite it by yourself. It allow you to create a website much faster than you could had been without it. 

But why do you want to use one? 

1. Save development time hence save cost

1. No need to reinvent the wheel (Unless for educational purpose)

1. Save cost

1. Chances that it will be more beautiful than you could had design yourself are very high

What are some of the example of CSS framework? 

1. [Bulma](https://bulma.io/)

1. [Bootstrap](https://getbootstrap.com/)

1. [Foundation](https://foundation.zurb.com/)

1. [UIKit](https://getuikit.com/)

1. Flexbox

If you are paying attention, yes, we had already covered Bulma in our third workshop. Of course there are much more CSS franework than what we had mention above. You can simply google **CSS Framework** to find out even more of them. There are a lot of them, and **IT IS OK TO NOT KNOW EVERY SINGLE ONE OF THEM**, because you don't use all of them at the same time. Master of one framework are better than you know every single framework yet master of none.

So now you ask if you want to learn outside of Bulma, are there any tutorial for it? 

Documentation are your best tutorial! 

Documentation can be found easily in the their website itself. It will usually call **Docs** or **Documentation**. Explore these CSS framework through the documentation and find out what suit you the most. There is no best CSS framework, but rather more suitable depending on the circumstances. 

#### Static Site Generator

Writing my own website is so tired, and all I need is just a static personal website or my own blog that can be static. What can I do to solve this problem? 

Static site generator is your answer. Static site generator allow you to only write the content and choose the theme that you want to have and generate a static website for you. Usually you will write your content in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and it will generate a nice website for you. If you think the template does not do what you want to, you can create your own template and generate the static website. After that, all you need to do is only constantly update your content.

Some of the example of static site generator can be found in [this website](https://www.staticgen.com/). 

In the website, it include a lot of different static site generator and they had include the official website for each of the framework, documentation can be found in their website too. 

Notable mention will be [Jekyll](https://jekyllrb.com/), because the site that you are currently viewing right now are made by Jekyll.

#### JavaScript

JavaScript had been covered in our 4th and 5th workshop. One is purely JavaScript, while the other are DOM. JavaScript allow you to have extra functionality in your website. During our JavaScript workshop, we did not covered everything in JavaScript due to time constrain. Therefore, we only cover things that are necessary to understand during DOM workshop. 

With that in mind, it is good to go through a JavaScript tutorial by yourself, not only to understand topic that we did not cover, but also understand topic that covered by us but not explain in much detail as those tutorial did. Fortunately, our club had quite a few JavaScript developer and they provide some really good JavaScript learning resources. 

**Tutorial**

1. [Eloquent JavaScript Tutorial](https://eloquentjavascript.net/)

1. [Freecodecamp Tutorial](https://www.freecodecamp.org)

1. [Codecademy JavaScript Tutorial](https://www.codecademy.com/learn/introduction-to-javascript)

1. [W3Schools JavaScript Tutorial](https://www.w3schools.com/js/default.asp)

After going through all the tutorial, you will realize that we had a lot that we had yet to covered, such as prefix and postfix increment, truthy and falsy value, for and do-while loop, etc. All of these will be covered extensively in all the tutorial that I had mention above. 

#### API requests with AJAX

What is API? API is application programming interface. What exactly is that? 

Just imagine you have a cloud server somewhere in China because renting server in China is cheap. Now imagine your server have a lot of your customer detail, include their username, password, name, phone number, etc and you making a website and you want to allow your customer to login and see their detail. So, how can it be done? 

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

**Tutorial**

1. [Freecodecamp Tutorial](https://www.freecodecamp.org)

1. [Codecademy Requests Tutorial](https://www.codecademy.com/courses/intermediate-javascript-requests/lessons/requests-i/exercises/requests-intro-i?course_redirect=introduction-to-javascript)

1. [W3Schools AJAX Tutorial](https://www.w3schools.com/js/js_ajax_intro.asp)

#### JavaScript Framework

What is a JavaScript framework and why do you need one? From [Wikipedia](https://en.wikipedia.org/wiki/JavaScript_framework), the definition of JavaScript framework is 

```
A JavaScript framework is an application framework written in JavaScript. It differs from a JavaScript library in its control flow:[1] a library offers functions to be called by its parent code, whereas a framework defines the entire application design.[2] A developer does not call a framework; instead it is the framework that will call and use the code in some particular way. Some JavaScript frameworks follow the model–view–controller paradigm designed to segregate a web application into orthogonal units to improve code quality and maintainability.
```

Oh my god, the definition from Wikipedia are so complex which full of jargon... Ok, basically JavaScript framework is a framework that allow you to run JavaScript in your own computer like any other application do, not just live inside the browser. With JavaScript framework, now you can do a lot more things, but most those will be cover in [backend](README.md#backend). For a small project, you might find JavaScript framework very overwhelming and exhausting, however it is better when doing a big scale project because it has a certain way of doing things, hence increase the code quality and maintainability. It make things more structured for us to understand. 

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

### Backend

Backend is the part in a web where it does all the business logic and data persistent. 