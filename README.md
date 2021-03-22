![hypermodularity](https://logo.hypermodularity.com/2/cover.png)

# hypermodularity.com
www hypermodularity.com

http://hypermodularity.com/

[hyper modularity](https://www.hypermodularity.com/)





## logo
https://lottiefiles.com/search?q=module&category=animations&animations-page=2



## The shared module

In the next chapter we're going to cover a critical type of module that you'll need to create in any reasonably sized application: the shared module.


## urls


The complexity and size of real world codebases for Javascript apps continues to grow larger and larger every year.
To combat this, codebases are often "modularized" for two primary reasons:

+ To provide a clear separation of concerns for the application's functionality
+ To easily implement app performance upgrades like code splitting and AoT compilation

In fact, modularization is now such an important part of building web apps that Angular requires you to architect your applications with it out of the box!

While AngularJS also had a module system, it was often ignored by developers as it often didn't provide enough advantages to make it completely necessary.

### Introducing NgModule

From the Angular docs:

    Angular Modules help organize an application into cohesive blocks of functionality.

Every time you add a new feature set into your application, it's a good idea to create a new module to contain it. However, you want to avoid creating unnecessary modules as well, so understanding when to create modules is a bit nuanced. 
We'll cover this in detail a bit later when we show real world examples.

###  The root AppModule

Per the Angular Style Guide, every Angular app needs to have a root module called AppModule that is responsible for importing all other modules & functionality that is required for the app to start. The Angular Team has an excellent resource that describes it in detail:
AppModule: The Root Module

It's worth noting that Angular services that need to act like singletons (which most services do) should be imported in the AppModule to ensure there is only one instance ever created during the lifecycle of the application.

If we take a look at our previous examples you'll see how we defined the app module in 


https://programmersought.com/article/5310963279/


https://clintberry.com/2013/modular-angularjs-application-design/


# Books
https://www.google.com/search?tbm=bks&q=modularity




Modularity: Understanding the Development and Evolution of Natural Complex Systems
https://books.google.de/books?id=xfW6mmAJWjwC



## Presentation

https://www.slideshare.net/johannes-weber/module-management-angularjs
