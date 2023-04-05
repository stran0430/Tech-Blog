# Tech-Blog

## User Story
```
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
WHEN I am idle on the site for more than a set time
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments
```
## Description
To build a tech blog, this app makes use of numerous files, database storage, and technologies. On the home page, users can view any blogs and select them to view the comments. It will be clear who posted both the article and the comments.

A user can sign up to establish an account or log in to an existing one if they want to create their own blog. Once they have logged in, they can access a dashboard where they can submit blogs. Additionally, they can visit other blogs and post comments there, providing their identity and the date.

The user can then log out to terminate their session, or a timeout is available.

## Table of Contents
- [Deployment URL](#Deployment-URL)
- [Repo URL](#Repo-URL)
- [Usage](#Usage)
- [Technologies Used](#Technologies-Used)


### Deployment URL


### Repo URL
https://github.com/stran0430/tech-blog


## Usage
To start the process, go to the deployed site

Then create an account or view the first few blogs and comments.

### Screenshot
<img width="1405" alt="Screen Shot 2023-04-05 at 17 51 33" src="https://user-images.githubusercontent.com/115510413/230220923-d41d7149-dfc7-4c9d-9024-038412246269.png">


## Technologies Used
The packages required to run are:
```
bcrypt
connect-session-sequelize
dotenv
express
express-handlebars
express-session
mysql2
sequelize
```

A database will need to be created first then seeded wih data.
