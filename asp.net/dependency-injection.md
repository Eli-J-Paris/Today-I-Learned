### What is Dependency Injection in an ASP.NET Core App

As applications begin to be built out and as code bases begin to increase in complexity its important to start thinking about how your applications architecture should look and behave. While there are multiple architectural design patterns one can utilize in their applications one of the most popular ones is Dependency Injection. 

 

### Now What is Dependency Injection?
Luckily for us Dependency Injection sounds scarier than it actually is. On a simple level Dependency injection is when you have a piece of code that uses another piece of code and instead of using that code directly it's passed in to that code instead. This process of passing in code is what is referred to as injection.

If this is all still a little fuzzy that's alright. Before being able to fully understand what Dependency Injection is, Its helpful to understand what Dependency in programming is.

<img width="296" alt="image" src="https://github.com/Eli-J-Paris/Today-I-Learned/assets/130601227/e47a7fb9-3c3f-4a1a-b700-40e1c5af1fff">

### What is it used for?
Utilizing dependency injection helps create a loosely coupled program vs creating a tightly coupled program. Coupling is a technical term used to describe the level of a relationship between two software components, oftentimes prefixed with either loose or tight.

###### Tightly coupled
Is when two or more components interact with one another and must be present and functioning at the same time.

###### Loosely coupled 
Is when components of an application can function independently. They’re detached from one another and are not obligated to rely on each other to perform their respective tasks.

As always there are advantages and disadvantages to designing a tightly or loosely coupled application over the years loosely coupled has become more popular.

### What is Dependency in Programming?

Simply put, dependency is the relationship between two components where one component is DEPENDENT on the other to work properly. This relationship can be Internal such as a class relying on another class or external such as utilizing third party software. 

If you would like to learn more about dependency check out this article What Are Software Dependencies.
- https://www.sonatype.com/launchpad/what-are-software-dependencies#:~:text=A%20software%20dependency%20is%20a,application%20depends%20on%20that%20library

### To Dependency Inject or to not Dependency Inject?

Recently dependency injection has become a popular design pattern to follow. Some of the advantages include.
- More easily maintainable and reusable code.
-  Allows for loose coupling implementation of code.
-  Is handy dandy for using and implementing interfaces.
-  Can more easily swap out implementation of code for newer or more refined version.
- Helps make unit testing a bit easier.

As with all things good there is a little bad to be aware of when considering to us dependency injection.

- Using this design pattern requires more discipline and effort to implement when developing software.
- Has the potential to make code harder to trace and track down because of the separate behavior from its construction.

Further Reading & Movie Night
- https://www.techtarget.com/searchapparchitecture/definition/dependency-injection
- https://www.youtube.com/watch?v=tTJetZj3vg0
- https://nonamesecurity.com/learn/difference-between-tight-and-loose-coupling/
- https://www.youtube.com/watch?v=J1f5b4vcxCQ
