# Technology Blog

## Table of Contents
* [Description](#Description)
* [Live Project](#Live-Project)
* [User Story](#User-Story)
* [Acceptance Criteria](#Acceptance-Criteria)
* [GitHub Repository](#GitHub-Repository)
* [Tests](#Tests)
* [Installation](#Installation)

## Description 
Technology Blog is a website that enables users to create technology related blogs, comment to existing blogs. 

## Live Project
The application is deployed in Heroku at https://morning-falls-13783.herokuapp.com/

**Built With**
* JavaScript ES5  
* JavaScript ES6  
* JSON
* Node.js 
* Express.js 
* npm bcrypt dotenv mysql2 
* npm sequelize connect-session-sequelize
* npm express express-handlebars express-session handlebars
* JEST
* MySQL
* Heroku
* JawsDB
* REST
* ORM
* OOP
* TDD
* MVC

## User Story

<details>
<summary>Expand</summary>  

    AS A developer who writes about tech
    I WANT a CMS-style blog site
    SO THAT I can publish articles, blog posts, and my thoughts and opinions
</details>

## Acceptance Criteria

<details>
<summary>Expand</summary>  

    GIVEN a CMS-style blog site
    WHEN I visit the site for the first time
    THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
    WHEN I click on the homepage option
    THEN I am taken to the homepage
    WHEN I click on any other links in the navigation
    THEN I am prompted to either sign up or sign in
    WHEN I choose to sign up
    THEN I am prompted to create a username and password
    WHEN I click on the sign-up button
    THEN my user credentials are saved and I am logged into the site
    WHEN I revisit the site at a later time and choose to sign in
    THEN I am prompted to enter my username and password
    WHEN I am signed in to the site
    THEN I see navigation links for the homepage, the dashboard, and the option to log out
    WHEN I click on the homepage option in the navigation
    THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
    WHEN I click on an existing blog post
    THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
    WHEN I enter a comment and click on the submit button while signed in
    THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
    WHEN I click on the dashboard option in the navigation
    THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
    WHEN I click on the button to add a new blog post
    THEN I am prompted to enter both a title and contents for my blog post
    WHEN I click on the button to create a new blog post
    THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
    WHEN I click on one of my existing posts in the dashboard
    THEN I am able to delete or update my post and taken back to an updated dashboard
    WHEN I click on the logout option in the navigation
    THEN I am signed out of the site
    WHEN I am idle on the page for more than a set time
    THEN I am automatically signed out of the site 
</details>

## GitHub Repository
The project's repo link: https://github.com/rosefrancis-tech/tech-blog

## Installation
In order to run the application in your local, follow the steps
* Install [Node.js](https://nodejs.org/en/), [MySQL](https://dev.mysql.com/downloads/windows/installer/8.0.html)
* Download the codes from [repo](https://github.com/rosefrancis-tech/tech-blog)
* In the root of the repo, create a file named `.env` and enter the database name, MySQL user and password like shown below.  
`DB_NAME='techblog_db'`  
`DB_USER='your-mysql-username'`  
`DB_PW='your-mysql-password'`  
* In the terminal navigate to the local repo 
* To install dependencies, run `npm install`
* To [create database](https://drive.google.com/file/d/1Z5hmoqcAQ3qq2GC4aOYkCr6VuG4_HmWX/view?usp=sharing), open MySQL shell and run `source db/schema.sql`  
* To start the application, run `npm start`  
* To exit, type `Ctrl+C` in terminal 

