# Final Project

## Description
Demonstrate everything you have learned thus far in the course. Apply the processes we have learned to build your app using Agile methodologies.


## Objectives

### Learning Objectives

After completing this project, you should…

* Understand how to come up with your own user stories.
* Understand how to put together wireframes.
* Be able to think about and sketch out the models and relationships of the data for your project.
* Be able to act as the develop and the client for a product.
* Know when to cut features and how to identify the core competency of your product.


### Performance Objectives

After completing this project, you be able to effectively use

* Balsamiq or pen / paper for wireframing
* Trello for your user stories
* Heroku for hosting your app
* UMLs for digraming your database structure



## Details

### Deliverables

* Create a GitHub repo for your final project. Read up on how to use markdown to format your project README if you don't already know how. Use this [Example README](/EXAMPLE_README.md) as a starting point.
	* [Markdown Basics](https://help.github.com/articles/markdown-basics/)
	* [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/)
* Watch this TED Talk. Fair warning: it's kind of cheesy and dated and might make you cringe, but some of the points are great for how to structure your project pitch.
	* [How great leaders inspire action](http://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action?language=en).
* Write up a short (one or two paragraph) description of your project keeping in mind the "golden circle" that was talked obout in the TED talk. Put it in your repo README.
* Balsamiq mockups or pictured of sketches of the pages and flow of your application.
	* Sketch out which pages will link to other pages with arrows.
	* Digitize these and include them in your repo with links in the README.
* A link to a trello board with a complete list of user stories for your app with estimates
	* User stories should start with: "As a <type of user> I want ..."
	* Inside of each user story create a checklist of all of the things you will need to do to complete that user story including things like testing and deploying.
	* Estimates should be either 1/2 day, 1 day, 2 days, or 3 days. **Anything greater than 3 days should be broken out into multiple smaller user stories.**
	* Add my trello account as a user on your trello board.
	* Link to your trello board in your README.
* Data models for your application in the README of the repo.
	* All of the different models that your application will need.
	* All properties for each model
	* The type of each property (see [waterline documentation](https://github.com/balderdashy/waterline-docs/blob/master/models.md) for options)
	* Any validation that you will have to do on the properties. Does it need to be a URL or email address, etc...
		* How are you going to do that validation on the front-end (custom with react or jquery)? Map out which libraries you will use on the front or back end.
	* Whether or not the property is required (true or false)
	* Whether or not the property is unique (true or false)
	* The relationship between each models (no relationship, one to one, one to many, or many to many)
	* Include these models in your README.
* Put together a list of APIs, js libs,  and gems that you will be using for your project. **TEST OUT ALL OF THESE OVER THE WEEKEND**.
	* This should also include any APIs that you will be using - including links to relavent documentation that describes how the API can be used to do what you want to accomplish.
	* **TEST OUT EVERY API AND LIBRARY THAT YOU WANT TO USE** - put together a demo of each one showing how it can be used (in a simple form) to accomplish what you need.
		* For APIs it might be just querying the API for the information you need and printing the information.
		* For any libraries it might be just getting their demo example working on your computer.
* Add links to your LinkedIn, Twitter, portfolio, etc. at the bottom of the repo README so interested people can contact you about your project.

### Requirements

* You should have at least 10 user stories.
* Your app must have multiple models that have relations between them.
* Your app must have authentication (with either devise, omniauth, or custom).
* Your app must be hosted on heroku.
* Your app must look good, be presentable, consistent, and work on mobile devices.
* Your app must contain atleast one react component.
* Your app must have be hooked into [Travis CI](https://travis-ci.org/) and [Code Climate](https://codeclimate.com/)
  * Test coverage must be at least 50%
* Your app must use one or (preferably) more of the following:
  * Pagination
  * Email (Mandrill)
  * Texting (Twilio)
  * Geolocation (Maps and/or storing user's location to calculate distances)
  * Remote APIs
  * PDF export
  * CSV export
