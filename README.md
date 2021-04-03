# Tech Blog
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<br>
A CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. This app follows the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.
<br />

![Blog site](https://github.com/FAC-73/primitive-notion/blob/main/assets/Application_demo.png?raw=true)
Watch the [video](https://drive.google.com/file/d/1MnX1TKSeZnrkm2WWYOwy_A2LwmL_cR61/view?usp=sharing)
<br />

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)


## User Story

```md
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```

## Acceptance Criteria

```md
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
```
  
## Description

Coming soon


## Installation
Clone the repo to your local development environment.

```md
git clone https://github.com/FAC-73/primitive-notion.git
```
Navigate to the primitive-notion folder directory using the command prompt.

Run `npm install` to install all dependencies. in terminal or bash
<br><br>
Run `node seeds` to seed the data
<br><br>
Run `npm start` to run the application in terminal or bash
<br><br>
Use http://localhost:3001 [or whatever terminal port you have specified] in Insomnia to run the server requests


## Licence
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<br />

## Contributing
[Kay Davis](https://github.com/FAC-73)
<br />

## Built with
- [Javascript](https://www.w3schools.com/jsref/default.asp)
- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [Sequelize](https://sequelize.org/)
- [mySQL](https://www.mysql.com/)
- [JSON](https://www.json.org/json-en.html)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [MySQL2](https://www.npmjs.com/package/mysql2)
- [InsomniaCore](https://insomnia.rest/products/insomnia)
- [Handlebars.js](https://handlebarsjs.com/)
- [Heroku](https://heroku.com/)


## Questions?

### GitHub Username:
[FAC-73](https://github.com/FAC-73)

###  ✉️ Email me:
[kaydavis21@googlemail.com](mailto:kaydavis21@googlemail.com)

### 📁 GitHub project repo:
[https://github.com/FAC-73/primitive-notion](https://github.com/FAC-73/primitive-notion)


