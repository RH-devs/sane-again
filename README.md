# SaneAgain
This platform is created for people to build an online community by sharing their anxiety stories, making positive comments to encourage others and help each other walk out of anxiety and depression! The target audience for this site are teens, adults and aged who are currently suffering from depression and anxiety..
It will be very useful to participants as they will be able to make comment, likes on every post on the website.

## UX

__SaneAgain__

Most people has got something bothering to say or even have been silently depressed about a particular thing. SaneAgain enables people to read about how to get rid of depression/anxiety or generally things bothering them. It also provides users with a way to make comments with others and gain more knowledge about topics posted on the website.

![sane-again](https://github.com/RH-devs/SANE-AGAIN/blob/main/static/images/saneagain_mockup.png)

__User Stories__

__An admin of this site should do the following:__

* As an admin, i should be able to approve Comments

* As an admin, i should be able to create Drafts

* As an admin, i should be able to Manage Posts

* As an Admin, i should be able to Paginate the Site

__A typical user of this site should do the following:__

* As a User, i should be able to log into the website

* As a User, i should be able to Comment on a Post

* As a User, i should be able to View like reactions

* As a User, i should be able to View Comments

* As a User, i should be able to Select a Post

* As a User, i should be able to Check all posts list

__A new user of this site should do the following:__

* As a new User, i should be able to register an account

* As a new User, i should be able to Select a Post

* As a new User, i should be able to Check all posts list

* As a new user to the website, I want to understand the purpose of the site and how to interact with it.


## Scope

The scope of this project is to create a simple, intuitive, and responsive website that acts as a respository of helpful posts that users can browse and contribute to by commenting.

The structure should adhere to convention and be simple and intuitive, ensuring the user always knows where they are, how they got there and how to get back to where they started.

The design should be simple, utilising the same colour palette,

Any addition features or functionally are out of scope at this stage.

__User Goals:__

* To select posts from different authors.
* To be able to comment on, read, and like posts.
* To be part of a social blogging platform.

__Website Owner's goals:__

* To build on and expand the community for people trying to find comfort in reading.
* To create a safe and welcoming platform for users to share their comments on posts created.
* The ability for admin to edit and delete posts to keep the platform safe and welcome for bloggers.

## Features

__Existing Features__
* User Registration: This allows new users to create an account so they can log in.
* User Log-in: This allows existing users to log in using their username or email and password. Passwords are hashed for security reasons. Log-in is required to read , like and make comments.
* A user must be logged in to like and make comments. 
* A user doesn't have to log in to view messages and number of likes on post.
* Logout : allows a user to securely logout of the page.

__Admin__
* Admin role - The admin can Create ,Read ,Update, and Delete blog posts.
* Admin is able delete comments written by users that is considered inappropriate.
* Admin is able approve comments written by users that is considered appropriate.

__Features Left to Implement__
* Allow users to create a profile and share their stories on the blog.
* Allow users to rate blogposts.
* Allow bloggers to search for posts based on users' ratings.
* Allow admins to block/suspend users when necessary.
* follower feature
* comments feature
* implement a better editor in the write a post page to ensure proper paragraghing/ design and possibly add symbols and image

__Site implemented Features__

Every page on this site also incorporates the following features:
* A logo in the top left hand corner, that not only forms part of the branding and design of the site but also as is consistent with a user's expectations, clicking the logo will return the user to the home page of the site.

* A responsive, collapsible navigation bar, allowing users to easily navigate the site on any device.

## Pages

### All users

__Home__

The home page introduced users to the site with a different posts for them to select and it directs them to full post page to read. There is also navigation button of register and login to be able make comments.

Here the both unregistered and registered users may view and read blogs posts created by the Admin. However, unregistered users can't make comments or like posts.

__Register__
The registration page allows a user to register an account. To register a user is required provide a username, email and password. Validation has been added to form. The Registration page also provides a link to the Log In page if a user has already registered and simply needs to log in, once a user is registered , he or she is redirected to the log in page.

__Log In__

The Log in page allows registered user to log in to their account in order to make comments and like posts. The Log In page also provides a link to the Registration page if a user hasn't yet registered.

__Created Posts__

This page displays a form to the user to enable them to create a new blog. The user first selects a category from a dropdown list, then enter the title of their blog, content,publish_date ,read_time, created_by and hashtags the content/text area allows up to 2000 words and is expandable. The user then clicks submit and their blog is saved in MongoDB and visible on the site. This page is not accessible to users that are not logged in.


__Admin Only__

* Categories
This is an admin only area and allows an admin to create, edit and delete posts on the front end. This page displays a list of categories available to users, the categories have an edit and delete icons to allow an admin to either make edits to a category or to delete one. The page also has an 'Add Category' button to allow an admin to create a new category.

* Database Design
All user generated content is stored in Postgres linked in Heroku. 


### Technologies

__Languages & Frameworks__

* HTML5 - Mark-up language using semantic structure.
* CSS3 - Cascading style sheet used to style.
* JavaScript - Programming language.
* Python - Programming language
* Favicon - was used for creating the favicon
* Gitpod.io - for writing the code. Using the command line for committing and pushing to Git Hub
* GitHub - hosting repositories
* GIT - Pushing code to repositories
* Django Summernotes
* Bootstrap

__Front End__

* Google fonts - for the font
* Font Awesome - for icons used

__Backend__
* Heroku
* Postgres 
* Beautifier - for helping to keep code tidy
* Random Key Gen - to generate a random secret key
* Power Mapper to check for browser compatibility
* Kanban for Project Planning
* Balsamiq wireframes - for planning of site flow, creating wire frames and general mind mapping

