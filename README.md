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

* Home

The home page introduced users to the site with a different posts for them to select and it directs them to full post page to read. There is also navigation button of register and login to be able make comments.

Here the both unregistered and registered users may view and read blogs posts created by the Admin. However, unregistered users can't make comments or like posts.

* Register
The registration page allows a user to register an account. To register a user is required provide a username, email and password. Validation has been added to form. The Registration page also provides a link to the Log In page if a user has already registered and simply needs to log in, once a user is registered , he or she is redirected to the log in page.

* Log In__

The Log in page allows registered user to log in to their account in order to make comments and like posts. The Log In page also provides a link to the Registration page if a user hasn't yet registered.


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
* Gitpod.io - for writing the code. Using the command line for committing and pushing to Git Hub
* GitHub - hosting repositories
* GIT - Pushing code to repositories
* Django - framework
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

## Testing

* I tested the site in the following ways:

* I used the inspector tool to test the site in all the screen sizes and devices available in the Chrome developer tool. In addition to this I also tested it on live devices, including but not limited to iPhone, iPad, MacBook Pro, MotoG7.

* I also viewed my site in multiple browsers including, Chrome, Firefox and Safari in terms of design, responsiveness and functionality

__Testing Tools__

* HTML Validator - checking the validity of code
* CSS Validator - checking the validity of code
* Pep8 Online - Testing and checking PEP8 compliance
* Am I Responsive - checking whether the site is responsive.
* DEV Tools - Lighthouse

__Validation reports__

All links were tested to ensure there were no broken links and that all links to external sites open in a new tab.
In addition to testing with the inspector tool, real devices and validation tools, I also work through a series of test cases, to ensure that the site met the users stories and that any functionality that was added worked as intended.

__User Story Test Cases__
* New Visitors
- As a new visitor to the website, I want to understand the purpose of the site and how to interact with it.
The home page of the site features a title and an introduction with an explanation of the purpose of the site and how to interact with it.
- As a new visitor to the website, I want to find blog posts and select which one to read without the need to register.
- There should no requirement to register to view blog posts. 
- As a new visitor to the website, I want to be able to register easily.
- The should be navigation is clear and has a item named 'Register/Sign-up', when a user clicks on this nav item they are brought to a simple form, with clearly labelled fields, placehold text and a clearly marked 'Register/Sign-up' button.

* Logged In Visitors
- As a logged in visitor to the website, I want to be able to read across selected blog posts.
- As a logged in visitor to the website, I want to be able to comment on blog posts.
-  As a logged in visitor to the website, I want to be able to like blog posts.
- As a logged in visitor to the website, I want to be given visual confirmation when I comment that it has been sent for admin's approval.

* Admin
- As an admin, I want to be able to approve or delete any comments. When an admin is logged in, the edit and delete buttons are available to them on all blogs allowing then to edit or delete any inappropriate comments.
- As an admin, I want to be able to easily add, edit or delete categories within in the site rather than having to access MongoDB.
- When an admin is logged in a new nav item is added called Categories. Clicking on this page allows an admin to view exisiting catgories, as well as edit or delete them. Additionally there is an add category button allowing then to add a new category on the front end.

__Functionality Test Cases__

Navigation:
* While logged out, you can see all the nav links listed below for logged out and unregistered users:
- Home
- log in
- register

* Home:
While user logged out, he/she will be able to see the following:
- The navigation links
- 6 paginated posts with images with informtion of the below:
title post
Created by
published date
- footer with quick links info , logo and copyright.
* Login
While logged in, make sure you can see all blogs and that any blogs that was created by you, now has the edit and delete button on them.
while logged in , make sure you can see blogs written by you on your profile page.
While logged in as an admin, make sure you can view all blogs and blog categories and that all categories blogs now have the edit and delete button. so the admin may delete inappropriate blogs created by users but may not edit blogs created by other users.
admin can delete and approve comments created by him /her
admin can also create and edit blog posts


## Lighthouse testing

- Accessibility
scored 84%

- SEO
scored 80%

- Best practices
scored 92%

- Performances
scored 95%

__Bugs__

During the development of this site I encountered a number of different bugs that have been now been fixed. A few notable bugs include the following:

During testing it was highlighted that a user could enter empty spaces and submit the forms. I search online and adapted my code based on information using the pattern attribute class="validate" and ensuring all fields were required. users can see a small text message advising them on how to fill the form incase they have gotten it wrong.

## Technology Configuration

__Heroku Postgres__

Heroku Postgres was used as the database to store the users details to set up Heroku  follow the steps below

- You will need to sign up to Heroku
- Once logged in click the create new app button
- Select the region closest to you and give the APP a name
- Go to the addons box is just search for Postgres, Select the Hobby Dev - Free plan and click Provision:
- Then add Heroku Postgres to your project.

### Forking

__Forking the GitHub Repository__

By forking the GitHub Repository, you can make a copy of the original repository in your own GitHub account. This means we can view or make changes without making the changes affecting the original.

- Log into GitHub and locate the GitHub Repository.
- At the top of the Repository there is a "Fork" button about the "Settings" button on the menu.
- You should now have a new copy of the original repository in your own GitHub account.
- You will need to install the requirements.txt using the following command the command line pip3 install -r requirements.txt
- You will need to set up your local environments and key value pairs for deployment

__Cloning__
- Making a Local Clone

- Log into your GitHub then find the gitpod repository

- Under the repository name there is a button that says, "Clone or download". Click on this button.

- If cloning with HTTPS "Clone with HTTPS", copy this link.

- Open Gitbash

- Change the current working directory to the location where you want the cloned directory to be.

- Type git clone, and then paste the URL you copied earlier.

- You will need to install the requirements.txt using the following command the command line pip3 install -r requirements.txt

- You will need to set up your local environments and key value pairs for deployment and running the application in your local environment.

# Deployment

This project is hosted on Heroku. It's been deployed using the following steps:

Sign up (new user) or sign in to Heroku account. I already had an account from previous projects, so only needed to sign in.
Click the button at the top right that says "New", select "Create new app" in the dropdown.
Choose an app name. Caution! This must be unique!
Select your region. In my case, this is Europe.
You'll be redirected to the Deploy tab of the new app.
Go to Deployment method. Select your prefered deployment method. As my code was already on Github, I chose the "Connect to Github" option. The following steps will be specific to this option.
Sign in to your Github account to allow Heroku access to repositories.
Search for your repo name. If you can't remember the specific spelling of the name, leave the input field blank and click "Search" to get a list of all your repos.
When you've found your repo in the list, click the "Connect" button.
You now have the choice to enable automatic deploys or deploy manually.
Your project will need to contain the following in order for Heroku to deploy it:
a Procfile: this specifies the commands that are executed by the app on startup. You can use a Procfile to declare a variety of process types, including:

Your app’s web server
Multiple types of worker processes
A singleton process, such as a clock
Tasks to run before a new release is deployed.
In the case of this project, the Procfile contains only a single line:

echo web: python app.py
a requirements.txt file. This tells Heroku which dependencies need to be installed in order for the project to run. It's created by using the command pip install + the name of any dependencies you have (for example, Flask needs to be installed for this project) in the terminal of your prefered editor, followed by the command pip freeze > requirements.txt which will write the installed dependencies to a text file which Heroku then installs using pip install requirements.txt.

Go to settings in the Heroku tab. Click "Reveal Config Vars". Add the relevant environment variables you've used in your project to the Config Vars so Heroku can access them. Specifically, for this particular project, that means the following Config Vars were added:
DEBUG (set to False to turn off Debug mode in the deployed version. Locally, in development, this variable was set to True.)
Deployment
This project is hosted on Heroku. It's been deployed using the following steps:

Sign up (new user) or sign in to Heroku account. I already had an account from previous projects, so only needed to sign in.
Click the button at the top right that says "New", select "Create new app" in the dropdown.
Choose an app name. Caution! This must be unique!
Select your region. In my case, this is Europe.
You'll be redirected to the Deploy tab of the new app.
Go to Deployment method. Select your prefered deployment method. As my code was already on Github, I chose the "Connect to Github" option. The following steps will be specific to this option.
Sign in to your Github account to allow Heroku access to repositories.
Search for your repo name. If you can't remember the specific spelling of the name, leave the input field blank and click "Search" to get a list of all your repos.
When you've found your repo in the list, click the "Connect" button.
You now have the choice to enable automatic deploys or deploy manually.
Your project will need to contain the following in order for Heroku to deploy it:
a Procfile: this specifies the commands that are executed by the app on startup. You can use a Procfile to declare a variety of process types, including:

Your app’s web server
Multiple types of worker processes
A singleton process, such as a clock
Tasks to run before a new release is deployed.
In the case of this project, the Procfile contains only a single line:

echo web: python app.py
a requirements.txt file. This tells Heroku which dependencies need to be installed in order for the project to run. It's created by using the command pip install + the name of any dependencies you have (for example, Flask needs to be installed for this project) in the terminal of your prefered editor, followed by the command pip freeze > requirements.txt which will write the installed dependencies to a text file which Heroku then installs using pip install requirements.txt.

- Go to settings in the Heroku tab. Click "Reveal Config Vars". Add the relevant environment variables you've used in your project to the Config Vars so Heroku can access them. Specifically, for this particular project, that means the following Config Vars were added:
- DEBUG (set to False to turn off Debug mode in the deployed version. Locally, in development, this variable was set to True.)
DISABLE_COLLECTSTATIC - This should be removed before the final deployment.
CLOUDINARY_URL
DATABASE_URL
SECRET_KEY
- Check the activity tab. The two most recent items in the list should read "Deployed" and "Build Succeeded" in their status.
- Click "Open App" in the top right side if this is the case, this will take you to the live site of the Blog It.
Check the activity tab. The two most recent items in the list should read "Deployed" and "Build Succeeded" in their status.
- Click "Open App" in the top right side if this is the case, this will take you to the live site of the ![sane-again](https://sane-again.herokuapp.com/).

* You can also deploy on CLI using the instructions below:
- Run the command heroku login -i and login when prompted. Then run the following command: 'heroku create your _app_name_here' to create a new app, replacing your_new_app_here with your preferred app name. This will create a new Heroku app and link it to your Gitpod terminal.
- You can then access the app through the Heroku Dashboard and setup your config vars.

* If you already have an app created on Heroku and want to deploy using the CLI, you can go through the steps below:
- Run the command heroku login -i and login when prompted. Then run the following command: 'heroku git:remote -a your _app_name_here' and replace your_app_name_here with the name of your Heroku app. This will link the app to your Gitpod terminal.
- Afer linking your app to the workspace with one of the above steps, you can then deploy new versions of the app by running the command 'git push heroku main' and your app will be dployed to Heroku.



