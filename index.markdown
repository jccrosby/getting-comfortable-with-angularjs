## What is AngularJS?
AngularJS is a framework that aids in and speeds up single-page application development. Built and improved to be modular and extensible, it is allows you to to create a toolset and your own framework to fit your application development needs. As a fairly mature (in JavaScript standards) framework that focuses on single-page applications, AngularJS provides well thought out and efficient solutions to problems that you’d encounter while developing single-page applications.   

## What do I need to know to get started with AngularJS?
There are a few terms that will help when discussing and learning Angular. Here are some of the top-level terms with some descriptions and a few more that you’ll hear, but I’ll cover later. 

### Dependency Injection
Sounds really complicated, but it is really just providing your system with the objects and data that it needs to operate. Kind of like the arguments that you pass to a method, the dependencies are passed into your controller, services, whatever by Angular. 

### Models & Scope
In angular the data lives in models. Models exist in a scope. The scope ties the view to the controller & data by providing an execution context. That context is is bound to the DOM. More simply, the scope is where the data and methods that build the view will exist. 

Scopes are inherited $rootScope -> $scope

### Controllers
Controllers are where your applications logic is going to live. Controllers are how you add data and methods to the scope so the view (DOM) can be affected. Creating a controller creates a new scope that inherits from the $rootScope. That new $scope is attached to a DOM element and since it inherits from the $rootScope, has access to the data from the $rootScope as well as the new data and methods you add to it in the new controller. 

### Views
What the user sees. Views render the data in whatever structure you need it to to get the user what they want. The view is the DOM and you attach your controllers to DOM elements. The data & methods in the $scope are what builds and adjusts the view. 

Templates, expressions, and binding

### Modules
A module is a container for your application. It houses the objects that will run when your application starts up. 

### Directives
A very powerful feature of AngularJS. Directives are what and how existing tags are extended and how you can create your own, new tags. 
### Things we’re not going to cover here
- Startup/Bootstrap
- Routes
- Services
- Filters
- Partials/Templates
- Shifting your focus

## Use the data not the DOM
Talk about state and how updating the data should allow the view to change to reflect the updates in the data.

## Angular 101
Hello, World (01)
A jQuery version
The AngularJS version
### Concepts
- Model
- Data bindings
- Expressions
The View & Control (02)
A jQuery version
The AngularJS version
Concepts
- Controller
- Scope
- Model
Using an additional library (03)
A jQuery version
The AngularJS version
### Concepts
- Other Libraries
- Structuring Things
## Structuring code 
Maintainability, modularity, reuse, working in teams

### Creating Modules  
Think of modules as a way to group your applications code into a container. Modules can contain controllers, services, directives, filters. They can also depend on other modules. 

Module Example: Creating a module (05)

#### Adding a controller to the module.  
Directives - extend the browser. 
Directives are one of the cooler features of AngularJS. They allow you to extend the functionality of existing tags and create your own.
 
Some examples of built-in directives:
- ngRepeat
- ngShow/ngHide
- ngSwitch

You can create your own directives too to augment existing or create new tags.
Directive Example: create a scale slider tag

## Summary
There is much more that AngularJS has that can be used to build your applications. Hopefully this gets you to where you are comfortable enough to get your application started. 