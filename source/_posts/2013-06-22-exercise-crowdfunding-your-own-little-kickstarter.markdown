---
layout: post
title: "[Exercise] Crowdfunding: Your own little Kickstarter"
date: 2013-06-22 07:39
comments: false
categories: 
---

#### Technical Goal
Today's exercise will give you additional practice with basic web design and development, particularly using Coffeescript, Stylus, and Jade. You will develop a single-page web application for crowdfunding your idea. It's like Kickstarter, but solely for your startup idea. For the purposes of this exercise, you will not need to power your web application with a back-end, i.e. data does not have to be persistent. You will only focus on developing an interactive front-end using the technologies we talked about so far in class.

In addition, this exercise will provide you with an opportunity to better write your idea to gather supporters as well as raise funds. You don't need to use the startup idea you have in class (although you certainly can) to complete this exercise.

**NOTE:** This exercise is highly open ended. Your mileage will vary depending upon your creativity.

#### Details

Using Jade (HTML), Stylus (CSS), and Coffeescript (Javascript), create a crowdfunder site to raise funds about a particular idea of yours. The following are the requirements for this exercise. However, feel free to go beyond the basic specifications.

- Your web page should contain the following:
	- Name of your project/idea
	- Short description of idea (in <= five words)
	- Your name and contact information
	- Details about your project (breakdown in different sections as you see fit)
	
- Your web application should allow users to add donation, i.e. accept money, Bitcoin, or the like. For the purposes of this exercise, you can simply have a textbox that accepts numbers. Use JS to handle input and prompts. Please handle the integrity of the input accordingly, i.e. no negative or zero donations, etc.

- Donations should be tied into a specific donor. Hence, you should also require name input for each donations and display them accordingly. That is, if Bob donates $10, then somewhere in your page should display 'Bob - $10' or something like that, and other donations should go along like that as well.

- Your web application should also display donation statistics, i.e. how much donations raised so far, how many more to go 'til goal is reached, or how many people donated specific ranges of donations. You may add other stats as you think appropriate or necessary.

- Add a comment system to your web application. That is, allow users to comment on your idea. You can choose to display comments by grouping or all at once, but please make sure to sort them in a specific ordering.

- Add a support button to your website. Users should be able to click a link or item to support your project and you should display updated number of supports in your page.

**NOTE:** Your data does not need to be persistent. That is, if someone reloads the page, it is OK to lose all inputted data. However, while the page is active, your application should display information accordingly.

**ANOTHER NOTE:** UI is important to attract donors! So prettify your stuff as much as possible. More than just the technology stack you're using, creativity is also key here. We haven't talked about UI/UX yet, but please be creative as much as possible.