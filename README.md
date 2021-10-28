![hypermodularity](https://logo.hypermodularity.com/2/cover.png)

# [HyperModularity](https://www.hypermodularity.com/)

Hypermodularity is an attractive principle for software and hardware architecture

+ e.g. by assembling a infrastructure of organisation from a large amount of elements
 
## some of the benefits:

+ the customized bricks are tested and ready to use.
+ production cost are significantly decreased 
+ reliability of the system is increased due to fewer single points of failure. 


<script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
<lottie-player src="https://assets3.lottiefiles.com/private_files/lf30_csdufwaz.json"  background="transparent"  speed="1"  style="width: 300px; height: 300px;"  loop autoplay></lottie-player>



## Definition of Modularity in Software Architecture

Modularity is a way to group related code together.
Most languages have modularity structures, such as packages in Java. 
Architects need to be aware of how products are packaged by developers and it has major architectural consequences. 
For example, if many packages are closely coupled together, it becomes more difficult to reuse one of them.


## Modular Reuse Before Classes

Developers before object-oriented languages can struggle about why there are so many different separation schemes. In 1968, a letter written by Edsger Dijkstra denigrated the popular use of the GOTO statement. This paper, illustrated by Pascal and C, led to the era of structured programming languages. Modula and Ada had a module programming structure, just like today's packages or namespaces.

Object-oriented programming languages became popular when new ways of reusing code were introduced.

A term used to describe code grouping is modularity. From a simplicity standpoint, grouping a large number of classes together in a monolithic application can make sense. However, when the time comes for the architecture to be restructured, the coupling becomes an obstacle to breaking the monolith apart. For software artifacts, such as components, classes, and so on, developers also need qualified names to differentiate different software artifacts from each other to reduce conflict.



## The shared module

In the next chapter we're going to cover a critical type of module that you'll need to create in any reasonably sized application: the shared module.


## AngularJS


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



##  Modularized and decentralized architecture based on micro- and nano- services.

+ Nanoservices
+ Microservices
+ Devops
+ Architecture




### Presentation

https://www.slideshare.net/johannes-weber/module-management-angularjs





## Articles

+ https://dev.to/workpebojot/architecting-modules-for-software-modularity-part-2-3bpc

+ https://programmersought.com/article/5310963279/

+ https://clintberry.com/2013/modular-angularjs-application-design/

+ https://link.springer.com/article/10.1007/s10202-008-0065-z



## Modularization – Satisfy Customers and Decrease Costs


Modularization is a method that can be employed during the product development process to create innovative products that customers love, while keeping production costs low. 
Key to a modular, customizable product is to identify which are the functions and parts of the product that are noticed and important to the customers. 
The rest of the product should be kept standard for as many product lines as possible.
That way you can offer your customers choices and give them a feeling of having this unique product they were looking for, while saving big in the background.

https://brainmates.com.au/general/modularization-satisfy-customers-and-decrease-costs/


## Books

+ https://www.google.com/search?tbm=bks&q=modularity


Modularity: Understanding the Development and Evolution of Natural Complex Systems
+ https://books.google.de/books?id=xfW6mmAJWjwC


## Example projects

+ [www.webstream.dev](https://www.webstream.dev/#/)


---

## Tom Sapletta
+ [Contact on linkedin](https://www.linkedin.com/in/tom-sapletta-com/)
+ [Tom Sapletta Blog - Embedded System Software & Hardware Developer](https://tom.sapletta.com/)
+ [Softreck Company - Leadership Through Software Development](https://softreck.com/)


---
+ [edit](https://github.com/hypermodularity/www/edit/main/README.md)

```
https://github.com/hypermodularity/www.git
```
