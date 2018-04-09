# TODO Application Documentation

One Paragraph of project description goes here

## Index

- [Getting Started](#getting-started)
- [Running the tests](#running-the-tests)
- [Medium Title](#medium-title) 
- [Small Title](#small-title) 


## About the Todo application

The Todo application is a simple online Todo list manager. New Todos' may be added, marked as complete and deleted. Completed Todos' are clearly marked with a tick and crossed out text. A down arrow at the top left of the page allows select all. And view options at the bootom of the screen allow for different views based on the status of the Todo being All, Active or Completed. The Todos' are saved locally to the browser, and will be shown when the page is reloaded. You may also double-click a Todo to modify it. The page is clean and simple, and there is no advertising to slow it down, so response is immediate.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

Clone or download the project into you web server's www folder. On certain servers it may be required to place the files in an html folder within the www folder.

```
Give the example
```



End with an example of getting some data out of the system or using it for a little demo

## Running the tests

The site includes the Jasmine test suite and the following test for the major functions of the site.

'''
controller
  should show entries on start-up
routing
  should show all entries without a route
  should show all entries without "all" route
  should show active entries
  should show completed entries
  should show the content block when todos exists
  should hide the content block when no todos exists
  should check the toggle all button, if all todos are completed
  should set the "clear completed" button
  should highlight "All" filter by default
  should highlight "Active" filter when switching to active view
toggle all
  should toggle all todos to completed
  should update the view
new todo
  should add a new todo to the model
  should add a new todo to the view
  should clear the input field when a new todo is added
element removal
  should remove an entry from the model
  should remove an entry from the view
  should update the element count
remove completed
  should remove a completed entry from the model
  should remove a completed entry from the view
element complete toggle
  should update the model
  should update the view
edit item
  should switch to edit mode
  should leave edit mode on done
  should persist the changes on done
  should remove the element from the model when persisting an empty title
  should remove the element from the view when persisting an empty title
  should leave edit mode on cancel
  should not persist the changes on cancel

'''

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Performance Comparison

The following is a comparison between this Todo site and a competitor, Todo List Me (http://todolistme.net). This site offers many more features but the core applications are similar allowing the comparison of the performance of key functionalities between the two.



