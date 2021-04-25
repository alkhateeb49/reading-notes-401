# Class 15

* ## OAuth <br/>
It starts with a simple, single-provider single-sign on, and works up to a client with a choice of authentication providers: GitHub or Google.

The samples are all single-page apps using Spring Boot and Spring Security on the back end. They also all use plain jQuery on the front end. But, the changes needed to convert to a different JavaScript framework or to use server-side rendering would be minimal.

All samples are implemented using the native OAuth 2.0 support in Spring Boot.

There are several samples building on each other, adding new features at each step:

simple: a very basic static app with just a home page and unconditional login via Spring Boot’s OAuth 2.0 configuration properties (if you visit the home page, you will be automatically redirected to GitHub).

click: adds an explicit link that the user has to click to login.

logout: adds a logout link as well for authenticated users.

two-providers: adds a second login provider so the user can choose on the home page which one to use.

custom-error: adds an error message for unauthenticated users, and a custom authentication based on GitHub’s API.

Single Sign On With GitHub
In this section, you’ll create a minimal application that uses GitHub for authentication. This will be quite easy by taking advantage of the autoconfiguration features in Spring Boot.

Creating a New Project
First, you need to create a Spring Boot application, which can be done in a number of ways. and generate an empty project (choosing the "Web" dependency as a starting point). Equivalently, do this on the command line:

$ mkdir ui && cd ui
$ curl -d style=web -d name=simple | tar -xzvf -COPY
You can then import that project into your favorite IDE (it’s a normal Maven Java project by default), or just work with the files and mvn on the command line.

Add a Home Page
In your new project, create index.html in the src/main/resources/static folder. You should add some stylesheets and JavaScript links so the result looks like this:

---
