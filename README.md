# Hyper Modularity book by Tom Sapletta
+ How to design self-managed modular distributed systems?
+ reusable metamodules in research, development and management


![Hyper Modularity Book Cover(2)](https://github.com/hypermodularity/www/assets/5669657/c6464457-96b3-4d9a-950f-6518c3078f53)


---
---
---


Co przyniesie rok 2222?

Rok 2022 przyniósł aplikacji ChatGPT pierwszy milion użytkowników w ciągu **5 dni** od jej publicznego udostępnienia.
Po dwóch miesiącach aplikacja osiągnęła poziom **100 mln** użytkowników, bijąc tym samym rekord!
TikTok, dotychczasowy lider, na uzyskanie takiego zainteresowania potrzebował 9 miesięcy, Instagram 2,5 roku, a Facebook około 5 lat.

Wielu pamięta te doniesienia medialne, wielu chciałoby również pochwalić się takim wzrostem w najbliższych miesiącach a nie latach, bynamniej w roku 2222 :) 

Ta książka jest właśnie dla Was!

+ Dla osób **optymalizujących** procesy dla **spersonalizowanych** usług
+ Dla **architektów** modularnych systemów
+ Dla **deweloperów** modularnego oprogramowania

Uczących się zawodu przyszłości: **projektanta systemów modularnych** w celu:
+ budowy kosmicznej stacji do zbierania energii słonecznej (Space Solar Power, SSP) 
+ optymalizacji sieci autonomicznych usług dla asystentów i robotów
+ personalizacji usług w oparciu o cyfrowego bliźniaka

---


**Tom Sapletta** programuje od czasów zx-spectrum, commodore i atari, ma za sobą prawie **2 dekady** doświadczenia zawodowego w międzynarodowych zespołach jako Researcher, DevOps, programista java, kotlin, python, javascript, php, perl, ...

W tej książce dzieli się doświadczeniem w projektowaniu i rozwijaniu **hipermodularnych** sieci oprogramowania.

Autor publikuje na [blog.hypermodular.com](http://blog.hypermodular.com) i dyskutuje z czytelnikami hipermodularyzacji na [forum.hypermodular.com](forum.hypermodular.com)

---
Więcej:
+ Zakup książki: [buy.hypermodularity.com](http://buy.hypermodularity.com/?2023)
+ Materiały do pobrania [download.hypermodularity.com](http://download.hypermodularity.com)
+ Projekt na github [github/hypermodularity](http://www.github.com/hypermodularity)


---
---
---


---
---
---



---
---
---



---
---
---


## This book answers these questions


+ What is Modular Design
+ Modular Design in Different Forms
+ Types of Modular Design
+ Modular Design in Advertising


---
Systemy hipermodularne cechują się zdolnością do elastycznego konfigurowania i skalowania oraz często zastosowaniem w środowiskach wymagających niezwykłej niezawodności i adaptacji.

Poprzez opisane metody i rozwiązania, dowiesz się jak optymalizować złożone projekty, niezależnie od branży.
W tej publikacji opisuję jak dotrzeć do sedna problemu, rozbić go na atomy i dowieźć rozwiązanie do klienta w sposób zautomatyzowany.
Poprzez zarządzanie najmniejszymi elementami, oszczędzasz czas i zwiększasz jakość budując zautomatzyowany biznes nawet w warunkach garażowych.
Cykl wytwarzania oprogramowania zmienia się nieustannie, tutaj otrzymujesz dostęp do wiedzy popartej doświadczeniem prawie 2 dekad zawodowej pracy Software Developera, DevOps-a, researcher-a.


 

Niezależnie do tego zajmujesz się oprogramowaniem, czy sprzętem, hipermodularyzacja pomaga w tworzeniu reużywalnych, wyspecjalizowanych elementów, obniżając koszty produkcji i rozwoju, zwiększając niezawodność systemu dzięki mniejszej liczbie pojedynczych punktów awarii.

OpenAI nie powstało wczoraj i pracowało na ten sukces wiele lat ...

Nawet jeśli dziś zaczynasz sam to być może zadajesz sobie pytania:

+ jaką architekturę wybrać?
+ jakimi zasadami się kierować?
+ jakich motedyk użyć?
+ i jaką strategię przyjąć?

Zapraszam do zapoznania się z odpowiedziami na te i inne pytania...

Zapraszam do odkrycia świata Hipermodularnego, gdzie poprzez tworzenie autonomicznych procesów, cyfrowych bliźniaków możesz skupić się na kolejne obszary projeku, organizacji, życia...



## The Benefits of using hypermodular approach:

#### Flexibility:
Hypermodularity allows for a highly flexible approach to creating and managing systems, products, or projects. It allows for easy customization and modification, making it easier to adapt to changing needs and requirements.

#### Scalability:
Hypermodularity allows for easy scalability of systems or products. It allows for the addition or removal of modules or components as needed, without affecting the entire system.

#### Resilience:
Hypermodularity allows for highly resilient systems that can withstand failures or disruptions. It allows for easy replacement or repair of individual modules or components, without affecting the entire system.

#### Efficiency:
Hypermodularity allows for more efficient development, deployment, and maintenance of systems or products. It allows for easy integration of different modules or components, reducing development time and costs.

#### Collaboration:
Hypermodularity allows for greater collaboration among team members working on different modules or components. It allows for easy integration of different components, making it easier to work together on complex projects.

#### Customization:
Hypermodularity allows for easy customization of systems or products. It allows for the creation of highly personalized systems or products, tailored to the specific needs of individual users or customers.

Overall, hypermodularity approach offers many benefits for creating and managing complex systems, products, or projects. 
It allows for greater flexibility, scalability, resilience, efficiency, collaboration, and customization, making it an ideal approach for many different applications.



## The architecture of highly modularized, easily reconfigurable, highly decoupled, self-contained and reusable components is referred to as a microservices architecture.

##  [Component-based software engineering - Wikipedia](https://en.wikipedia.org/wiki/Component-based_software_engineering)

> **Component-based software engineering** (**CBSE**), also called **component-based development** (**CBD**), is a branch of software engineering that emphasizes the [separation of concerns](https://en.wikipedia.org/wiki/Separation_of_concerns "Separation of concerns") with respect to the wide-ranging functionality available throughout a given [software system](https://en.wikipedia.org/wiki/Software_system "Software system"). It is a reuse-based approach to defining, implementing and composing loosely coupled independent components into systems. This practice aims to bring about an equally wide-ranging degree of benefits in both the short-term and the long-term for the software itself and for organizations that sponsor such software.
> 
> Software engineering practitioners regard components as part of the starting platform for [service-orientation](https://en.wikipedia.org/wiki/Service-orientation "Service-orientation"). Components play this role, for example, in [web services](https://en.wikipedia.org/wiki/Web_service "Web service"), and more recently, in [service-oriented architectures](https://en.wikipedia.org/wiki/Service-oriented_architecture "Service-oriented architecture") (SOA), whereby a component is converted by the web service into a _service_ and subsequently inherits further characteristics beyond that of an ordinary component.
> 
> Components can produce or consume events and can be used for [event-driven architectures](https://en.wikipedia.org/wiki/Event-driven_architecture "Event-driven architecture") (EDA).


### Component-Oriented Design - COD

Software design approach that focuses on designing highly modularized, easily reconfigurable, highly decoupled, self-contained and reusable components we call Component-Oriented Design (COD).
Component based development is growing in popularity. And it presents a viable alternative to choosing between a monolith and microservices. 

### Why Use Component Based Architecture?

In this book, we present the benefits of component based development and how teams can switch to a component based architecture in few steps.

#### benefits

Component based architecture stays up-to-date, without rebuilding it from the scratch. 

That makes component based architecture a better fit for large, complex system

The modular components can be combined, decoupled, reused

How to Design Component-Oriented Software?

how to move to component based development from your existing monolith?

+ do not refactor, build a new smaller modules
+ connect a component/package/service in a logical stream of process
+ adopt the new function/logic throughout the process
+ support both the old and the new models simultaneously through format data


### Steps to a Successful Migration

When it comes to breaking up your monolith into component based development:

+    Focus on software delivery approaches and upskilling team members.
+    Build out the minimum infrastructure needed to deliver independently deployable components (e.g., containerized microservices) that expose self-service APIs.
+    Start tracking technical issues for new and legacy, including:
+        Counting errors released to production.
+        Service availability.
+        Time to remediate.
+    Consider cloud deployment options (as appropriate).
+    Implement basic monitoring for new and legacy.
+    Implement automation wherever possible.
+    Migrate in atomic steps.
    



+ about modular programming principles

Modular programming is a software engineering approach that involves breaking down a program into functional, independent modules. Each module is designed to be highly decoupled and self-contained, which allows it to be reused and reconfigured with ease.


A web application can be broken down into several smaller modules, such as a user authentication module, a content module, a payments module, and so on. Each module is designed to be independent and reusable, so that the overall application can be easily reconfigured or extended as needed.


A game engine can be broken down into several smaller modules, such as a graphics engine, a physics engine, a sound engine, and so on. Each module is designed to be independent and reusable, so that the overall engine can be easily reconfigured or extended as needed.



### macromodules and hypermodules


+ what are macromodules?

Macromodules are collections of components or modules that have been grouped together in order to form a larger, more complex system. They are typically used to create a system that is more efficient and cost effective than if the components were bought and assembled separately. Examples of macromodules include CPUs, memory boards, and hard disks.

+ what are hypermodules?

Hypermodules are collections of modules that have been grouped together to form a larger system that is more complex than a single module. They are typically used when a system needs to be highly modularized and easily reconfigurable, such as in an Artificial Intelligence (AI) application. Examples of hypermodules include neural networks, fuzzy logic systems, and computer vision systems.



+ what are a differences between macromodules and hypermodules?

The main difference between macromodules and hypermodules is in the complexity of the system they are used to create. Macromodules typically consist of components that are already integrated and are designed to create a single, larger system, while hypermodules are designed to be reconfigurable and modularized, allowing for more complex systems to be created. Additionally, macromodules are usually designed to be as cost effective as possible, while hypermodules are typically designed for speed and accuracy.


### supermodules and hypermodules?

+ what are supermodules?

Supermodules are a type of software module that is designed to be highly reusable, self-contained, and scalable. They are typically composed of multiple smaller modules that are connected together in order to perform a specific function or set of functions. Supermodules are designed to be used in multiple applications and to be easily customized and integrated into existing software.


+ what are hypermodules?

Hypermodules are a type of software module that is designed to be highly extensible and configurable. Unlike supermodules, hypermodules are not necessarily self-contained, but rather require other modules in order to function properly. Hypermodules are typically used to extend and enhance existing software applications, allowing them to perform more complex tasks than they would be able to do on their own.


+ What are a differences between supermodules and hypermodules?

The main difference between supermodules and hypermodules is that supermodules are self-contained and typically used in multiple applications, while hypermodules require other modules in order to function properly and are typically used to extend and enhance existing software applications. Supermodules are also typically designed to be highly reusable, while hypermodules are designed to be highly extensible and configurable.


### macromodularity and hypermodularity

+ what mean macromodularity?

Macromodularity is a software design approach that focuses on designing large and complex systems by breaking them down into smaller components, or modules. It is a way of organizing software components into distinct parts that can be built, tested, and maintained separately, while still working together as part of the larger system. This approach can help software developers create more robust and maintainable systems.

+ what mean hypermodularity?

Hypermodularity is a software engineering and architecture approach that is focused on dynamically creating and managing flexible, modular software systems. It involves building software components as highly independent, loosely coupled modules, and then using a platform or framework to dynamically manage how those modules interact and work together. This approach allows for more flexibility and scalability than traditional monolithic software architectures.


+ What are a differences between macromodularity and hypermodularity?

The main difference between macromodularity and hypermodularity is in the level of granularity of the modules. Macromodularity is focused on breaking down large and complex systems into smaller components, while hypermodularity is focused on creating highly independent and loosely coupled modules. Additionally, macromodularity focuses on static module design, while hypermodularity is focused on dynamic module design and management.

### multimodularity and hypermodularity

+ multimodularity

Multimodularity is the ability of a system to be composed of multiple, distinct modules that can be combined and recombined to create different configurations. This allows for flexibility and scalability, as well as the ability to modify or add components without having to completely rebuild the system.


+ hypermodularity

Hypermodularity is a concept in which a system is composed of multiple, loosely coupled modules that can be connected and recombined in a variety of ways. This allows for a high degree of flexibility and scalability, as well as the ability to modify or add components without having to completely rebuild the system.

+ differents between multimodularity and hypermodularity

The main difference between multimodularity and hypermodularity is in the degree of coupling between the modules. Multimodularity is composed of distinct modules that are tightly coupled and cannot be easily recombined, while hypermodularity is composed of loosely coupled modules that can be connected and recombined in a variety of ways. Hypermodularity provides a higher degree of flexibility and scalability.


# [HyperModularity](https://www.hypermodularity.com/)

Hypermodularity is an attractive principle for software and hardware architecture.

Infrastructure of an organisation 

+ e.g by assembling the infrastructure of an organisation from a large amount of elements.
 
 
## What Does Modularity Mean?

In software engineering, modularity refers to the extent to which a software/Web application may be divided into smaller modules. Software modularity indicates that the number of application modules are capable of serving a specified business domain.

Modularity is successful because developers use prewritten code, which saves resources. Overall, modularity provides greater software development manageability.

Modern business issues grow on a continuous basis - in terms of size, complexity and demand. Enhanced software capability requirements force developers to enhance developed systems with new functionalities.

Software engineering modularity allows typical applications to be divided into modules, as well as integration with similar modules, which helps developers use prewritten code. Modules are divided based on functionality, and programmers are not involved with the functionalities of other modules. Thus, new functionalities may be easily programmed in separate modules.

+ [What is Modularity? - Definition from Techopedia](https://www.techopedia.com/definition/24772/modularity)

##  Modular programming 

Modular programming is a software design technique that emphasizes separating the functionality of a program into independent, interchangeable modules, such that each contains everything necessary to execute only one aspect of the desired functionality.

A module interface expresses the elements that are provided and required by the module. The elements defined in the interface are detectable by other modules. The implementation contains the working code that corresponds to the elements declared in the interface. Modular programming is closely related to structured programming and object-oriented programming, all having the same goal of facilitating construction of large software programs and systems by decomposition into smaller pieces, and all originating around the 1960s. While the historical usage of these terms has been inconsistent, "modular programming" now refers to the high-level decomposition of the code of an entire program into pieces: structured programming to the low-level code use of structured control flow, and object-oriented programming to the data use of objects, a kind of data structure.

In object-oriented programming, the use of interfaces as an architectural pattern to construct modules is known as interface-based programming.[citation needed] 

+ [Modular programming - Wikipedia](https://en.wikipedia.org/wiki/Modular_programming)


## Modular Design


Modular design allows for modifications to systems, recombination of existing capabilities and upgrade of system elements, to enable competition, innovation, rapidly responding to a changing environment, etc.(see also Systems Engineering (SE) Guidebook, Section 2.2.5 Modular Open Systems Approach). Designing for modularity is a key technical principle for implementing a modular open systems approach (MOSA) and is a complementary piece to the open system practices in contracting. The major tenet of a modular design strategy is to develop loosely coupled modules, where modules can be decoupled, separated or even re-arranged in a major system platform and major system components developed under the program, as well as major system components developed outside the program that will be integrated into the Major Defense Acquisition Program (MDAP). When designing for modularity, the system should be appropriately partitioned into discrete, scalable, self-contained functional elements by decomposing and decoupling the functions of a system. This functional partitioning results in elements that can now be composed into modules that can be reconfigured or even replaced.

Acquisition programs implementing a modular design provide flexible system designs, which allow for the replacement or recombination of subsystems and components. It is important for the program management to understand the expected benefit from modular design as part of implementing a MOSA strategy. This understanding provides guidance to the system realization, on which enabling elements (e.g., standards, contract clauses, engineering tools, etc.) to use. MOSA benefits are usually categorized into six individually useful areas, which often overlap: risk reduction; cost savings/cost avoidance; increased competition; enhanced interoperability; application of innovative elements; and ability to realize technology upgrade opportunities easily.

+ [Modular Design](https://www.dau.edu/tools/se-brainbook/Pages/Design%20Considerations/Modular-Design.aspx)


## About Hypermodularity

Hypermodularity is about objects not about actions, we combine processes with objects.

Hypermodularisation is a continouous process focused on atomisation of the system objects.


I'ts like a rain-worm, you cutted into the pieces and it still functions, but at a higher level


You get a smaller part with the same functionality.


With the smaller size of a module the following benefits comming up.

+ modules get more specialised
+ such a specialisation brings about higher quality
+ 

What if I get more functionality at the same size.

We atomize the objects to bring it to make them more specialised.

It's a sinn to atomize something's only if you can 

The all questions are about hyper modularity.

What we want to get is the increease quality.

## Process over code

What I can propose is to build the code based on DSL and prepare a documentation based on patterns.
I read a book about SCRUM (https://www.amazon.de/Scrum-Doing-Twice-Work-Half/dp/B00NTP70AQ) 
and must say that the scrum can't improve it, so what can help? maybe some methodology to improve the communication on processes,
where meet all people, so this is what I call #hypermodularity, what can to improve the process not just a code.



## For whom?


Some people are doing many things during whole life and some are just enjoy awhile.

Some colleage was very effective at work
I was surprised he had a family and 2 childrens.
Looks like to have family give the power and determination to reach the goals!

I see the same in my case,
There is documented coincides with the establishment and expansion of the family.
Wife and 2 childrens don't stopped my carrer, but helped increase the number of implemented projects.
 
It's very wondering experience for me.

When you are a parent, you don't have many hours at your disposal, rather they are torn quarters of an hour.
That's why I decided to write a book about it: Hypermodularisation in real projects, exactly what give me many benefits to finish a project in small steps, even you have the family ...



## Imagine it

Imagine your Company that is doing better service, automatic every day 
Based on Industry 4.0 and decentralized global network based on 5g and 6g, 
Automatized infratsructure, managed by artifactial intelligence
Be leader, grow without borders and continuously 
every day, hour and second.


## Continous hypermodularity

With Continous hypermodularity we are going to defined smaller and better processes, that can work togheter without stopping them on the stream!



### Synonyms 

+ Super Modularity
+ Extreme Modularity

### Tags:

+ Modular architecture
+ Architecture Flow


## Definition of Modularity in Software Architecture

Modularity is a way to extract each part of code, such functions as a generic part instead of group related code together.
Most languages have modularity structures, such as packages in Java, with hypermodularity we based ons separated functions.



## Why make a Modularization 

+ To provide a clear separation of concerns for the application's functionality
+ To easily implement app performance upgrades like code splitting and AoT compilation

In fact, modularization is now such an important part of building web apps that Angular requires you to architect your applications with it out of the box!

While AngularJS also had a module system, it was often ignored by developers as it often didn't provide enough advantages to make it completely necessary.



## Benefits of Modularization

+ the customized bricks are tested and ready to use
+ production cost are significantly decreased 
+ reliability of the system is increased due to fewer single points of failure. 


## Satisfy Customers and Decrease Costs

Modularization is a method that can be employed during the product development process to create innovative products that customers love, while keeping production costs low. 
Key to a modular, customizable product is to identify which are the functions and parts of the product that are noticed and important to the customers. 
The rest of the product should be kept standard for as many product lines as possible.
That way you can offer your customers choices and give them a feeling of having this unique product they were looking for, while saving big in the background.

https://brainmates.com.au/general/modularization-satisfy-customers-and-decrease-costs/


# The way

Some people are doing many things during whole life and some are just enjoy awhile.

How to focus on continuous development?

When you are a parent, you don't have many hours at your disposal, rather they are torn quarters of an hour.

That's why I decided to write a book about it: Hypermodularisation in real projects, exactly what give me many benefits to finish a project in small steps, even you have the family ...




# Modularity vs Hyper modularity

+ perfectionism in modularization 
+ simplify to the limit
+ give independence
+ that it should be still usefull 


## What is an application

An apllication is a program with an interface


## What is an Interface

An interface is a first layer to interact with an logic program.


## What is a Module

+ an application extension
+ works inside application


## What is a Library

it's a defined and good designed generic function/helper or many function focused on specific area 


## What is a Helper

Helper it's small generic part in context of program


## What is a Package

It's an independent library to be use in a program



# Hyper modularity process


+ Split the smallest possible reusable elements

## What is the different between Modularisation and hyper modularisation

modularization is focusing on *grouping* the generic parts 
while hyper modularization is focusing on *splitting* the specific parts



## What is a Hyper modularity 

+ it's not just about grouping as model,
+ it's not just about extract small independent generic parts 
+ its' about the best solution for specific usage


## Hyper modularity results

huge result wiht litlle energy involved.
+ that's the leverage mechanism 
Cost reduction, lifetime design, and radical hypermodularity, are some of our keys to maximizing platform scalability towards


<script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
<lottie-player src="https://assets3.lottiefiles.com/private_files/lf30_csdufwaz.json"  background="transparent"  speed="1"  style="width: 300px; height: 300px;"  loop autoplay></lottie-player>



## Architecture of Systems, level of Modularisation

Module API can be invoked not only via HTTP API but via different infrastructure adapters
It's important to distinguish between different APIs (and contracts) on different levels.

Depending system the modules might be hidden.
It might be delegated to the messaging/event infrastructure altogether.

+ At class level - hide its state behind methods,
+ At the module level - hide its classes behind the module API,
+ At the system level - hide its modules behind the system API,
+ Encapsulating at different levels of architecture makes it possible to tackle complexity.



# Hypermodularity on monolith


## Packages, Dependencies, Classes

based on packages and namespaces the Classnames are overrided, but not each function/class method can be overrided.
So we should based on sperated functions to make it.

Going forward with such idea it's better to create each function separatly.

In another way, The Architects need to be aware of how products are packaged by developers and it has major architectural consequences. 
For example, if many packages are closely coupled together, it becomes more difficult to reuse one of them.


## Modular Reuse Before Classes

After "structured programming languages" era software developers started working with object-oriented languages,
today there are so many different separation schemes, so
it's easier to make one step forward to functional without some abstarctions such classes.

Modula and Ada had a module programming structure, just like today's packages or namespaces.

Object-oriented programming languages became popular when new ways of reusing code were introduced.


## Modularity in practice

A term used to describe code grouping is modularity.

hyper modularization is the process of extracting the code into the smallest possible parts, e.g. extracting functions from classes meeting the expectations of "Single Responisbility" and "Dependency Injection" 

From a simplicity standpoint, grouping a large number of classes together in a monolithic application can make sense. However, when the time comes for the architecture to be restructured, the coupling becomes an obstacle to breaking the monolith apart. For software artifacts, such as components, classes, and so on, developers also need qualified names to differentiate different software artifacts from each other to reduce conflict.


## The shared module

In the next chapter we're going to cover a critical type of module that you'll need to create in any reasonably sized application: the shared module.


# Hypermodularity on services layer


##  Modularized and decentralized architecture based on micro- and nano- services.

+ Nanoservices
+ Microservices
+ Devops
+ Architecture


## microservices -> nanoservices

What is the differend

On microservices we are working with packages and many classes to build some independent part osf system which can be independet service

+ DB

+ Auth

+ + roles


## layers

With more advanced servcies with independent latyer for auuthorisation, API, ...
We can just create one by one FaaS Functions as a Service using all of layers

We call it annoservices


The nanoservices based on existing infrastructure



# Packages modularity


## modularity in existing packages

how to make it step by step

how to extract from one packages all of functions?


## Articles

+ https://dev.to/workpebojot/architecting-modules-for-software-modularity-part-2-3bpc

+ https://programmersought.com/article/5310963279/

+ https://clintberry.com/2013/modular-angularjs-application-design/

+ https://link.springer.com/article/10.1007/s10202-008-0065-z


11 Principles Supported by Softreck's Extreme Manufacturing

The Test Driven Design aspect and Contract First Manufacturing are unique


## Contract-First Design

design the interface to other modules before designing the module


## Test Driven Development

design a series of tests that determines whether it will work, prior to doing design work
   

## Extreme Learning

in order to further a zero-waste development process, we focuses on training in practice, we produce lean instructionals intended for rapid learning.
This means that we optimize existing instructionals to facilitate the learning curve of advanced development techniques - especially with the interest of bringing people up to speed from zero. We like working with rapid-learning novices, as such people can become effective without the industrial inertia (old and prejudiced design ideas).


## Optimize for change

agility, adaptability of design is foremost to achieve desired result (complete, functional, minimal viable product)


## Object-Oriented, Modular Architecture

Modularity allows build a large system in parallel, as long as all the interfaces are well-defined for the modules. 
Modularity allows for a complete Product Ecology to emerge - for closed-loop manufacturing cycles. 
Modular architecture allows us to optimize 'borrowing' from other projects such that the development process is globally collaborative.
   
   
## Iterate the Design

Create the test that your design should pass.
Create the simplest design possible that enables the test to pass.
Improve the design to be simpler or more elegant.  Repeat this process ("Iterate on the design") until improving this component is no longer the highest value work you can do.
   
## Agile Hardware Design Patterns

wrapper (interface to the interface), common materials, tech recursion (invest in tools that make components and that make materials), 
Lifetime Design (so that hardware can be repaired easily)
  
  
## Continuous Integration Development

iterate continuously between product test, design, and manufacturing. This involves Design for Manufacturing, Design for Disassembly, Design for Fabricability, Design for Maintainability.
Product Service Systems allows testing as a scalable enterprise model for open source hardware.
Our current beta testing for build efficiency of this model is ongoing with our 
Extreme Manufacturing Workshops.
   
 
## Continuously Deployed Development

How to go to market fast? Flexible Fabrication concept. Digital fabrication assist. Open Design. Open Source R&D capacity, rapid prototyping, integrated R&D lab a la Edison.

## Scaling Patterns

Create teams for each module. Teams can work in parallel. Multiple teams can work on same module. Different teams can work on different aspects - design, build, documentation, prototyping, testing. Teams should have open communication channels, such as Work Log on our wiki or Dozuki structure, or video uploads, plus Forums, Stack Exchange, Design Sprints, and Leader Training Workshops. 


## Workshops Team and Customer

Scrum of Scrums, Product Owner and Scrum Maseter. Clear Customer Visible Value is generated and iterated. 
Chief Product Owner (CPO) sequences and refines the Portfolio Product Backlog continuously.
User stories are the requirements. Scrum Masters negotiate with other Scrum Masters for resources. 
All work completed satisfies the quality metric called the Definition of Done. Product owner maintains backlog and clarity. Scrum master maintains transparency of product delivery via documentation. Global remote effort can be maintained by heavy documentation typical of Open Source. 


## Documentation Flow

Heavy Documentation is Key to a Lean Process - which appears counterintuitive at first but is relevant to solving wicked problems.


## Partner Patterns

Easy sourcing from many partners. Wrapper is key to this flexibility - an interface of the interface design. 
Design collaboration with industry. 
University Collaborations for R&D. 
Wide portfolio of Freelancers to do design, build, and service along a Product Service System model.



# hyper modularity in another areas


    What is Modular Design
    Modular Design in Different Forms
    Types of Modular Design
    Modular Design in Advertising
    
 


## Network

 Networks with high modularity have dense connections between the nodes within modules but sparse connections between nodes in different modules. Modularity is often used in optimization methods for detecting community structure in networks. However, it has been shown that modularity suffers a resolution limit and, therefore, it is unable to detect small communities. Biological networks, including animal brains, exhibit a high degree of modularity. 
 


## Abstraction and AI

abstraction is depends context, so it can be good in some context, not ewerywhere, that's why I support personally Native Technologies, Microsoftsolutions are full of abstractions, but AI don't need it, so what is the future?
AI or Microsoft?



## Modularity is the king

That's why with modularity we can handle AI skills to build us better technology world, wit rapidly development and documented such describing world with words



### for abstraction friends

There is nothing wrong if abstraction is describing business logic for a human.
We need it till AI is not used to create hypermodular application by itself.
If AI is responsible for streaming application there si no more necessary to create abstraction.

What AI need?
native modular code written in native technologies.
AI is build the businnes logic over personalisation based on BIG DATA
It works such Black BOX with:
+ input
+ output
+ config


## Books

+ https://www.google.com/search?tbm=bks&q=modularity


Modularity: Understanding the Development and Evolution of Natural Complex Systems
+ https://books.google.de/books?id=xfW6mmAJWjwC


## Example projects

+ [www.webstream.dev](https://www.webstream.dev/#/)


---

## About Tom Sapletta

+ [Contact on linkedin](https://www.linkedin.com/in/tom-sapletta-com/)
+ [Tom Sapletta Blog - Embedded System Software & Hardware Developer](https://tom.sapletta.com/)
+ [Softreck Company - Leadership Through Software Development](https://softreck.com/)


## Sponsored by:

+ [Softreck - Leadership Through Software Development](https://softreck.com/)




---
+ [edit](https://github.com/hypermodularity/www/edit/main/README.md)

```
https://github.com/hypermodularity/www.git
```
