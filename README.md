# The Tech Blog

## Description
A mysql database and CMS-style Blog built using Model View Controller (MVC) paradigm. Built using MySQL2, Express, Sequelize, Bulma, Handlebars and dotenv.

## Screenshots
<img width="1440" alt="ScreenShot1" src="https://user-images.githubusercontent.com/65192910/92327767-b20ced00-f021-11ea-98c9-68fd545f142d.png">
<br>
<br>
<br>
<img width="1440" alt="ScreenShot2" src="https://user-images.githubusercontent.com/65192910/92327770-b46f4700-f021-11ea-9897-e86ba5d6b180.png">

## Deployed Application
https://secure-lowlands-66841.herokuapp.com/

## User Story
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions

## Acceptance Criteria
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

## Table of Contents
  - [Description](#description)
  - [Screenshots](#screenshots)
  - [Deployed Application](#deployed-application)
  - [User Story](#user-story)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Testing](#testing)
  - [Contributing](#contributing)
  - [Questions](#questions)

## Installation
`npm init`

`npm install sequelize`

`npm install mysql2`

`npm install dotenv`

`npm install express`

`npm install express-handlebars`

`npm install express-session`

`npm install connect-session-sequelize`

`npm install bcrypt`

## Usage
Run the following command at the root of your project.
`mysql -u root -p`

Enter your password when prompted.
Run `source db/schema.sql`

Run `quit`

Run `npm start`

Pull up your browser and view the page at `localhost:3001`

## Testing
No testing is set up at this moment. Tested externally through Insomnia Core.

## Contributing
Rachel Fritz

## Questions
 - Find me on GitHub: [rachelf0] (https://github.com/rachelf0) 
  - If you have any questions, please email me at: rachelfritz0@gmail.com
  - This README was generated with ❤️ by (https://github.com/rachelf0/tech-blog)
