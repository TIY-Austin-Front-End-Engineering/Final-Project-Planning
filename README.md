# Final Project Planning

## Description
Go through this assignment to come up with a solid game plan and project requirements for your final project.


## Objectives

### Learning Objectives

After completing this assignment, you should…

* Understand how to come up with your own user stories.
* Understand how to put together wireframes.
* Be able to think about and sketch out the models and relationships of the data for your project.


### Performance Objectives

After completing this assignment, you be able to effectively use

* Balsamiq or pen / paper for wireframing
* Trello for your user stories

## Details

### Deliverables

1. Create a GitHub repo for your final project. Read up on how to use markdown to format your project README if you don't already know how. Use this [Example README](/EXAMPLE_README.md) as a starting point.
	* [Markdown Basics](https://help.github.com/articles/markdown-basics/)
	* [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/)
1. Watch this TED Talk. Fair warning: it's kind of cheesy and dated and might make you cringe, but some of the points are great for how to structure your project pitch.
	* [How great leaders inspire action](http://www.ted.com/talks/simon_sinek_how_great_leaders_inspire_action?language=en).
1. Write up a short (half page) description of your project keeping in mind the "golden circle" that was talked obout in the TED talk. Put it in your repo README.
* Develop user stories for your project
	* User stories should start with: "As a &lt;type of user&gt; I want to &lt;goal/desire&gt; so that I can &lt;benefit&gt;"
	* Inside of each user story create a checklist of technical and non-technical tasks that you will need to complete in order to accomplish that user story including things like testing and deploying.
	* Add an estimate for the number of hours that each technical task in your checklist will take. Your options are 0, 0.5, 1, 2, 3, or 5. If something is going to take more than five hours then you should break it into two or more smaller technical tasks. Remember that tasks always take longer than you think they will! A 5 hour estimate for for the Iron quizzes project took more like 2.5 days.
	* Make your trello board public and link to it in your project README.
1. Balsamiq mockups or pictured of sketches of the pages and flow of your application.
	* Sketch out which pages will link to other pages with arrows.
	* Digitize these and include them in your repo with links in the README.
1. Data models for your application in the README of the repo. Even if you are not building out a back-end, you should still think about how your data will be stored in this format. Use [draw.io](https://www.draw.io/) to map out your models. Each model should include the following information:
	* All properties for each model
	* The type of each property
	* Any validation that you will have to do on the properties. Does it need to be a URL or email address, etc...
		* Think about how are you going to do that validation on the front-end? [underscore](http://underscorejs.org/) and [validator.js](https://github.com/chriso/validator.js) are your friends here. 
	* Whether or not the property is required (true or false)
	* Whether or not the property is unique (true or false)
	* The relationship between each models (no relationship, one to one, one to many, or many to many)
	* Include these models in your README.
1. Put together a list of APIs and libraries that you will be using for your project. **TEST OUT ALL OF THESE OVER THE WEEKEND**.
	* This should include any node modules, your front-end framework, your back-end framework (if any - probably Parse), your database (if any)
	* This should also include any APIs that you will be using - including links to relavent documentation that describes how the API can be used to do what you want to accomplish (eg. google maps, filepicker, etc.)
	* **TEST OUT EVERY API AND LIBRARY THAT YOU WANT TO USE** - put together a demo of each one showing how it can be used (in a simple form) to accomplish what you need.
		* For APIs it might be just querying the API for the information you need and console.log'ing the information.
		* For any libraries it might be just getting their demo example
1. Add links to your LinkedIn, Twitter, etc. at the bottom of the repo README so interested people can contact you about your project.

### Requirements

* You must have at least 10 user stories.
* You must have at least
	* three data models that relate to each other in some way or...
	* one data model and use at least one API, framework or library that we did not discuss in class


## Additional Resources

* Read [Markdown Basics](https://help.github.com/articles/markdown-basics/)
* Read [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/)
