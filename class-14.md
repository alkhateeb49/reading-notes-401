# Class 14<br/>
* ## Spring Security overview <br/>
Sooner or later everyone needs to add security to his project and in the Spring ecosystem you do that with the help of the Spring Security library.<br/>
![Stack](img/authentication.png)<br/>
### What is Spring Security and how does it work?<br/>
At its core, Spring Security is really just a bunch of servlet filters that help you add authentication and authorization to your web application.<br/>
It also integrates well with frameworks like Spring Web MVC (or Spring Boot), as well as with standards like OAuth2 or SAML. And it auto-generates login/logout pages and protects against common exploits like CSRF.<br/>
* * Authentication : That means your application needs to verify if the user is who he claims to be, typically done with a username and password check.<br/>
* * Authorization : In simpler applications, authentication might be enough: As soon as a user authenticates, she can access every part of an application.<br/>
### Web Security<br/>
Spring Security in the web tier (for UIs and HTTP back ends) is based on Servlet Filters, so it is helpful to first look at the role of Filters generally. The following picture shows the typical layering of the handlers for a single HTTP request.<br/>
### Working with Threads<br/>
Spring Security is fundamentally thread-bound, because it needs to make the current `authenticated` principal available to a wide variety of downstream consumers. The basic building block is the `SecurityContext`, which may contain an `Authentication` (and when a user is logged in it is an `Authentication` that is explicitly authenticated). You can always access and manipulate the SecurityContext through static convenience methods in SecurityContextHolder, which, in turn, manipulate a `ThreadLocal`.<br/>

---