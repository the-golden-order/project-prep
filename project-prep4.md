# Group Project: Begin Wireframes & Software Requirements

## Wireframes

It is now time to begin preparations for your Group Project.

The next step for group projects is to begin to generate wireframes for each page in your application.

## Tasks
Wireframes allow you to experiment with the look and feel of a website without committing any code.  
Create your wireframe in a digital tool. Whiteboard wireframes will not be accepted.

Provide an image of your wireframes in the readme of your project.

## User Stories

Start out by creating at least 5 user stories for your approved project. The outline/requirements for user stories can be found [HERE](https://codefellows.github.io/common_curriculum/projects/UserStories)

*1. Each story in your project management board should contain:*

* User Calls API
* As a user I want a site to search existing music and add it as my favorite
* The App will call to an existing music API and draw in results for the user to choose from 
* App successfully calls the API and renders results on the page with an "add" button
* [LucidChart](https://lucid.app/lucidchart/3afcc42b-6ac0-41d8-a345-286ecfa7ea8f/edit?invitationId=inv_71d90b39-98e7-4b3e-915a-1452133bafc8)

*2. Each story in your project management board should contain:*

* User Logs In
* As a user I want to be able to log into the site using my google account
* The app will incorporate the use of Auth0
* The app will successfully bring up google login on click and in the backend send token for verification
* [LucidChart](https://lucid.app/lucidchart/3afcc42b-6ac0-41d8-a345-286ecfa7ea8f/edit?invitationId=inv_71d90b39-98e7-4b3e-915a-1452133bafc8)

*3. Each story in your project management board should contain:*

* Navigation
* As a user I want to be able to navigate the site easily and effectively 
* Nav bar, with a home page, a user profile page, an about us (the devs) page 
* Clicks to the nav bar links successfully move to new route(page)
* [LucidChart](https://lucid.app/lucidchart/3afcc42b-6ac0-41d8-a345-286ecfa7ea8f/edit?invitationId=inv_71d90b39-98e7-4b3e-915a-1452133bafc8)


*4. Each story in your project management board should contain:*

* Style
* As a user I want my site to be aesthetically pleasing 
* CSS, so Much CSS (Rainbow button! :D BURN IT BUTTON!)
* Acceptance of group members thinking it pretty
* [LucidChart](https://lucid.app/lucidchart/3afcc42b-6ac0-41d8-a345-286ecfa7ea8f/edit?invitationId=inv_71d90b39-98e7-4b3e-915a-1452133bafc8)

*5. Each story in your project management board should contain:*

* Database
* As a user I want to be able to save my favorites for viewing later
* The music the user searches will be able to be "added" and saved to a mongodb independent of the site
* The music saves and renders properly upon login of the user. 
* [LucidChart](https://lucid.app/lucidchart/3afcc42b-6ac0-41d8-a345-286ecfa7ea8f/edit?invitationId=inv_71d90b39-98e7-4b3e-915a-1452133bafc8)

## Software Requirements

Using the [Software Requirements Document](https://codefellows.github.io/common_curriculum/projects/SoftwareReqs), create a new file within your main GH repo named requirements.md.  
Include in this doc the required information for your software reqs for your project as a whole.
[Our Requirements Doc](/project-prep/requirements.md)

## Domain Modeling

Draw out the entities for your project and how they are related to each other.  
Determine the relationships between the functions/methods and entities of your app.

Include in your domain model the names and data types of your entities and their properties.

Do some research on domain modeling and create your own diagram that represents your app. Here are some helpful resources as a starting point:

* [Brief introduction to Domain Modeling](https://olegchursin.medium.com/a-brief-introduction-to-domain-modeling-862a30b38353)
* [Domain Modeling](https://www.scaledagileframework.com/domain-modeling/)
* [Domain driven architecture diagram](https://medium.com/nick-tune-tech-strategy-blog/domain-driven-architecture-diagrams-139a75acb578)
* Include this domain model in the README.md file located in your project’s GitHub repo.

## Using a Database? Make an Database Schema Diagram

If you are using a database of any kind in your project, draft out what your schema will look like by creating a diagram of all your application data models, each in it’s own collection (or table).

Be sure to identify the relationships (if any) between each of your data models:

* Does a single item in your database “belong to” just one other item in your database? For example, a person has one passport, and a passport belongs to a single person.
* Does a item in your database “belong to” multiple other items in your database? For example, a house has many residents, and each resident has one primary house.
D* o many items in your database relate to many other items in your database? For example, a band has many musicians, and a musician can be in many bands.
* Also, include for each seperate collection:

      1 .The name of each property stored in the collection.
      2. The required data type.
      3. An indication if this collection is associated with another collection.

Include this diagram in your readme, accompanied by an explanation of each data model and it’s responsibility in the application.