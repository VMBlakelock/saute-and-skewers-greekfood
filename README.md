<img src="assets/images/destination-date-night-mock-up.png">

# Saute & Skewers | Greek Food 

*Share favourite Greek recipes with the community*

*Deployed to [Heroku](https://https://dashboard.heroku.com/) and stored in [Github](https://github.com/)*

<hr>

## Contents

- [Introduction](#introduction)
- [Aim](#aim)
- [Purpose](#purpose)
- [UX](#ux)
- [The 5 Planes of content strategy](#the_5_planes_of_content_strategy)
- [Features](#features)
- [Technologies and Frameworks](#technologies_and_frameworks)
- [Defensive Design](#defensive_design)
- [Testing](#testing)
- [Evaluation](#evaluation)
- [Deployment](#deployment)
- [Credits and References](#credits_and_references)
- [Websites Reviewed](#websites_reviewed)
- [Acknowledgements](#acknowledgements)

<hr>

## Introduction

With visitors from all over the world Greece is notably a favourite destination to all tourists. One of Greece's well known highlights is by far it's food.

From street food to quality cuisine and finally Mama's homecooked treats, the Greek have a wide variety of superb delights to offer.

This site allows the owner(admin) user to showcase their best loved recipes and hopes to gain traffic in the form of registered users to form a fantastic database of user favourites.


<hr>


### Aim

To create a functional website that allows users to manipulate data using the CRUD functionality.

Prime technologies to be used in the project are HTML/CSS/Javascript/Python/Flask and MongoDB.

### Purpose

Saute & Skewers is a Greek food website where users can view recipes stored in the sites database, however registered users can also manipulate their own data using the create, read, update and delete - CRUD functionality.

It is hoped that all users to the site will find the website to be of interest and of use. Registered users have the added benefit of actively being part of a community.


<hr>


## UX

## User stories

There are three types of users for this website, users stories for each are discussed below:

### Guest User

As a guest user I want to:
 - navigate around the site easily.
 - find a navigation bar that links to other pages when clicked. 
 - understand the sites purpose upon landing.
 - be able to view various content on the site.
 - be able to click social media icons to link out to other Saute & Skewer pages.
 - have the option to register to the site to see more.

### Registered Account

As a registered user I want to:
 - still be able to see the guest user content.
 - log into the site easily.
 - log out successfully.
 - have buttons to click to login, log out and submit data.
 - be able to add my own recipes to the site.
 - add recipes in an functional fashion.
 - edit my recipes if a mistake is made.
 - be able to delete my recipes should I wish.

### Admin User

As an admin user I want to:
- have full access to the site to ensure all content is viable.
- have access to be able to add more of my own recipes to the site.
- edit any content posted by me or by users of the site.
- have access to delete dormant or incomplete entries added to the site.


### Website Owner

The website owner would like users of the website to:
-  Interact with the site.
-  Enjoy the site and use it as a useful tool to find Greek food recipes.
-  Contribute to the site to create a vast selection of interesting data.

The website owner would like the website design to: 
- be clean and crisp looking with colors and a theme that portrays Greek Culture.
- have Greek images that creates an instant attraction to the site.
- have whitespace to create flow.
- have a footer containing social media icon links.

<hr>

<img src="static/pexels-greek-flag.jpeg">


## The 5 Planes of content strategy

### Strategy

- Saute & Skewers is a functional website. It allows simple usage to provide a great way to add and share content. 

- It features the 3 core languages of web development HTML, CSS and Javascript, as well as Python and Flask. It is deployed to a MongoDB database. 

- There is a clear brand that draws users and entices interactions.

- Users who discover Saute & Skewers, easily grasps it's concept - how it works and what it's output is.

- Saute & Skewers has the potential of not only being a content sharing site, it could potentially become a business site. Adding a few addtional features and marketing the site well could mean Saute & Skewers could generate revenues.

- During research there where other sites found that had the same concept, although the Greek aspect was minimal. 


### Scope 

- The site was developed with the intention of allowing users to build a database of their own recipes.

- The database of choice to build with was NoSQL - MongoDB.

- It was scoped to provide ease of use.

- Have the CRUD functonality.

- House a home page, registration page, log in page, log out page.

- Be responsive on all devices.

- Be visually appealing that incorporated Greek culture in the front-end design.


### Structure

- Saute & Skewers site structure was created from the UX user stories - therefore developed with pages that where required to enable users to sign up and add data.

- All pages are designed identically with 3 sections - a Navbar, content area and a footer.

- The Home page has a main image and 'Welcome' text. 
- The Highlights page shows a selection of recipe content and images for all users to view.
- The Register page has a basic registration form with a button and a link to login if already registered.
- The Login page has a basic login form with a button and a link to register if not already a member. 
- Once logged in the Login page becomes a Profile page, this shows a 'Welcome back' text, a few enticing words and a link to the 'Add Recipe' Page
- The Add Recipe page is where users add their own recipes once they submit the recipe it takes them to the Recipes page.
- The Recipes page is the home of user recipes already added. This is data stored in the database.
- Finally the Log out page displays, a 'You have been logged out message' and the same Log in view.

### Skeleton

Wireframes where created with only the main pages of the site in mind. Therefore only four where initially created.

These Desktop and Mobile wireframes demonstrate the basic design and structure of the site and the required elements each page needed. 

All wireframes were created using [Balsamiq](https://balsamiq.com/wireframes/).


Desktop:

[Home](wireframes/base-desktop.png)
[Register](wireframes/register-desktop.png)
[Login](wireframes/login-desktop.png)
[Recipes](wireframes/recipes-desktop.png)


Mobile:

[Home](wireframes/base-mobile.png)
[Register](wireframes/register-mobile.png)
[Login](wireframes/login-mobile.png)
[Recipes](wireframes/recipes-mobile.png)



### Surface 

Front-end visuals where based on:
 - A great brand design.
 - Traditional Greek colours.
 - Powerful images.
 - Enlighting text in which it is anticipated that the user would feel positive and maybe daydream to another world.

Colours and fonts therefore where important to promote traditional greek culture, with a tempting, feel good reaction.
With the Greek flag and its symbolic colours of blue and white, the sites aim was to incorporate this into its design. 

Users will see that Saute & Skewers chose a simplistic design with ample whitespace to provide an instant attraction on site opening.


<hr>

## Features 

### Existing Features

Multiple pages: The site has multiple responsive pages each with its own purpose and uses a simple scroll movement to provide easy navigation. 

Navbar: A navbar that links to the site pages, this changes dependent on the users status: Logged in, Logged out.

Button: The buttons when clicked confirm user actions.

Hyperlink: There is a hyperlink on the 'register page' and the 'login page' to revert user to an alternative area dependent on their action.

Social Media Links: Saute & Skewers has various Social Media accounts therefore icons for these are found in the footer.


### Future Features

Saute & Skewers - Future features could include:

- Having a larger database library for guest users to view.
- 
- An image field where users can upload images of their own added Greek foods.
- Users being able to create a profile page.
- A badge or icon level that registered users of the site could achieve, when X number of entries have been added - i.e - Top Contributer.
- A blog that promotes more of Greece - locations, its culture aswell as it foods.
- A messenger area where users can chat to each other live on the site.
- An e commerce shop where users could order greek foods and merchandise.

<hr>

## Technologies and Frameworks 

#### Technologies
- HTML
- CSS
- Javascript
- Python
- JSON

#### Frameworks
- [JQuery](https://jquery.com/)
- [Flask](https://www.fullstackpython.com/flask.html)
- [Materialize](https://materializecss.com/)

#### Database
- [MongoDB](https://www.mongodb.com/cloud/atlas/)

#### Text Editor
- [Gitpod](https://gitpod.io/)

#### Version Control
- Git

#### Hosting Platform
- [Heroku](https://https://dashboard.heroku.com/) - For the live deployed site
- [Github](https://github.com/) - To house the sites repository

#### Developer Tools
- Google Dev Tools

#### Validation sites
- [W3C Markup Validation](https://validator.w3.org/)
- [Jshint](https://jshint.com/)
- [PEP8](http://pep8online.com/)


<hr>

## Defensive Design

*Defensive design is the practice of planning for contingencies in the design stage of a project or undertaking. Essentially, it is the practice of anticipating all possible ways that an end-user could misuse a device, and designing the device so as to make such misuse impossible, or to minimize the negative consequences.*
[Wikipedia](https://en.wikipedia.org/wiki/Defensive_design/)

......................

### Testing

Testing was undertaken during the creation of this site, manual testing included tests on various devices. W3C Markup Validator, validation check was ongoing throughout the project development.
Pep8 compliance ......

Below highlights the main issues and bugs found during the development.


#### Issue 1

Initial routing wasnt correct, data was coming through to recipes.html as id forgotton the index.html

#### Issue 2



#### Issue 3

Needed more pages adding to site to allow for guest user and session user interaction

#### Issue 4

Materialize Carousel wasnt loading wellm the links kept breaking

#### Issue 5

#### Issue 6


Validation sites
- When validating the code for HTML and CSS errors where found and rectified. Mostly simple errors and typos.
- JShint for JS validation found there where xxx warnings, however many was of the same error. Unfortunately a fix wasnt implemented due to lack of understanding on how to resolve them and to time constraints. 
  Here are the errors 
  - **
  

### Browsers tested

- Chrome: Using Google Developer Tools - Chrome was used for testing on Laptop, Tablet and Android devices.

- Safari: Safari wasn't used for testing on an I phone or Mac, due to not having physical access to these type of devices. However they were viewed on Google Dev Tools.

### Devices tested

On final testing session the below devices where used here are the outcomes.

Mobile:
- Android - Samsung Galaxy A40 - Outcome: Site works perfectly. No bugs found. All is responsive.
- Android - Samsung Galaxy A20 - Outcome: Site works perfectly. No bugs found. All is responsive.
- Android - Samsung Galaxy S10 - Outcome: Site works perfectly. No bugs found. All is responsive.

Laptop:
- Toshiba Satellite C850 - Outcome: Site works perfectly. No bugs found. All is responsive. 


<hr>


## Evaluation

- Overall the design and development of this site is ................. It has all the basic requirements of a functional website and meets the project criteria.
- Most of the user stories where met, with the exception of .... editing user content.. probabably better to just delete or block user..............
- Many future features could be added to provide more interactive activity, functionality and imagery.
- Branch testing - No branch testing was undertaken....
- Manual Testing was undertaken .....Werkzeug ..........................more testing was required..
- Some front-end design changes where made during the build due to varying factors:
    - Materialize image carousel, looked good but didnt load well. Also the developer found it difficult to change the prebuilt images and the links kept breaking.
    - The site was to have 4 pages initally but it was discovered early in development that more pages would be required.

<hr>


## Deployment

#### Heroku:




##### Github:

In order to deploy the project to [GitHub](https://github.com/) Pages from its GitHub repository, follow the below steps:

1. On menu bar, select the 'Settings' tab.
2. Here, Scroll down to the GitHub Pages section.
3. In 'Source' click the drop-down menu labelled None, click and select Master Branch.
4. Once selected, Master Branch page will automatically refresh, the website will now be deployed.
5. Head back to the GitHub Pages section here you can retrieve the link of the deployed website.

If you want to run this project locally, we must clone the project for Github:

1. Under the repository name, click the green "Clone or download" button on the right.
2. A dropdown 'Clone with HTTPs' section appears, here copy the clone URL for the repository.
3. In your local IDE open Git Bash.
4. Change the current working directory to the location where you want the cloned directory to be made.
6. Type 'git clone' and paste the URL you copied.

- Example: git clone  = https://vmblakelock.github.io/saute-and-skewers-greekfood/
7. Press Enter. Your local clone is now created.


<hr>


## Credits and References

Personal credits go out to the following people:
- Spencer Barriball and excellent mentor who guided and assisted in the development of the project from inception to completion. 

Tutor Support
- Tim Nelson from tutor support who clarified issues within Cloud 9 videos and Gitpod usage.


Web References
- [Wikipedia](https://en.wikipedia.org/wiki/Defensive_design/)
    - Used to determine the exact meaning of defensive design.

<hr>


#### Websites reviewed

Websites reviewed and used during the creation of this project.

- [Balsamiq](https://balsamiq.com/)
  - Used for creating the wireframe mocks.
  
- [Bootstrap](https://getbootstrap.com/)
  - Researching carousel functionality, although wasnt used in the project.

- [Codeacademy](https://www.codeacademy.com/articles/what-is-crud/)
  - Article referring to "what is CRUD and its uses".

- [Google Fonts](https://www.fonts.google.com/basic-syntax/)
  - Used for choosing inital font.

- [Jshint](https://jshint.com/)
  - Validation testing of Javascript.

- [Markdownguide](https://www.markdownguide.org/basic-syntax/)
  - This website was used to refresh knowledge on how to use Markdown.

- [Materialize](https://materializecss.com/)
  - Documentation and code on Navbar, CSS colours and buttons.

- [Pexels](https://www.pexels.com/)
  - Used for site Images.

- [RandomKeygen](https://www.randomKeygen.com/)
  - Site to select a secure SECRET_KEY password.

- [StackOverflow](https://stackoverflow.com/)
  - Various research throughout.

- [Techsini](https://techsini.com/multi-mockup/)
  - Used for Mock Up Images.

- [Tech with Tim](https://www.youtube.com/watch?v=mqhxxeeTbu0&list=PLzMcBGfZo4-n4vJJybUVV3Un_NFS5EOgX)
    - A series of You Tube tutorial videos to gain greater understanding of Flask.

- [W3Schools](https://www.w3schools.com/basic-syntax/)
  - Reviewed and used frequently throughout the design of this project.

- [W3C Markup Validation](https://validator.w3.org/)
  - Validation testing of HTML and CSS.

<hr>


## Acknowledgements

Slack and the wonderful community of students past and present for thier motivational pushes.

My mentor Spencer Barriball for his profound knowledge and assistance in the development of the website.

For additional support and guidance Tutor Support guided me.

The developers own personal experiences during the creation and development of this project.


*created for education purposes only*

