# 2nd Report

## Requirements: Introduction, Purpose/Scope, and Description
Requirements engineeing is the process of defining, documenting and maintaining requirements taking into accont user and client needs in order to arrive at a definition of system, hardware or software requirements in order to respond to those needs. 
According to Barry Boehm requirements are "designing the right thing" as opposed to software engineering’s "designing the thing right"(Boehm, 1981).

When it comes to Scoping requirements frequently start with only one idea of the project. 
This happens because clients don't often know exacty what they want and usualy have limited knowledge about what they are asking. Scoping is iterative as the product's functions become clear and more realistic as time goes on and understanding increases between the clients and the developers. 

Analysis of the data gathered in order to develop the project is often driven by the "5 Ws" approach:
* What are the system's goals?
* What objects are involved?
* Where is the system located?
* When should things happen?
* Why is the system necessary?

This is how Requirements are used on order to develop a project that goes side by side to the clients' and users' ideology making sure that they get what they need.

Next we will take a look at how Requirements took part in the development of Cozy-Photos. 

## Specific Requirements and Features
The current features of Cozy Photos are quite simple, it's a small cloud platform to create albums of photos that you can share between friends only through email, even though they plan to add other ways of sharing the content. The app let's you organize your photos with albuns with a name and small description and upload photos by "drag n' drop" or manualy. 
Even though, right now, this is all there is to Cozy Photos the team is always open for suggestions and requests from clients and users.

Even though we didn't get an answer from the team about clients request and user needs, we already knew that their forum is the most common way to report a bug or submit a feature request, but while on the their [blog](https://blog.cozycloud.cc), we found a post about the results of a survey they did about the future commercial offer of Cozy. 
This survey was posted on three platforms: [Twitter](https://twitter.com/MyCozyCloud), their website, [cozy.io](https://cozy.io/en/) and in the newsletter. The questions were about the number of applications used, what were the essential applications on the day-to-day use of Cozy, what were the qualities expected for a paid service and a hosting provider. In conclusion, this survey purpose was not only try to study future needs, but also learn how the current application is being used.
In summarize, Cozy team is obviously very thorough about clients requirements. There's a constant comunication and feedback from the users through the forum, but also through some surveys shared on Twitter, their website and their newsletter. 

### Outside Development
As stated in their website, the Cozy developers clearly instate that they intend for cozy to also work as a web development learning tool. 
This way they allow for users who whish to develop to reuse the data already stored in the Cozy, they also want users to take the code apart, study it and "hack it to your heart's content." 
By allowing data reuse they what people to build new services on top of the user's data. The user's developed apps can then be introduced to the Cozy community so that feedback is given and the product improved. 
But nowere is it stated that the "external projects" can enter the main app functions. 
A question about this has been sent to the developers.

Besides having open source code and insisting on having users "toying" with their code deveoping for themselves Cozy also has a mentorship program to help building personal apps. They created a [Developer Space](https://dev.cozy.io) so that anyone can find what they need to understand Cozy technically and to develop applications and konnectors.
Topics covered by the mentorship are: code training, debugging or improving the design of user's apps. Cozy is a perfect platform for learning Node.js, Express.js, React.js and Angular JS and how these frameworks are used in real-word software development.

To those not adept in the programming department cozy offers a lot of ways to help with the project. They ask for anyone that can to translate de applications and documentation, to test the app on all the avaiable devices, answer forum questionnaires, try to replicate 
issues reported by other users, write tutorials and release notes, improve doccumentation, among other available options.
They also provide a Documentation's Roadmap with what they plan to add by order of relevancy. 

## Use Cases
> A use case is a sequence of transactions in a system whose task is to yield a measurable value to an individual actor of the system

A use case is a list of actions/steps, defining the interactions between a role and a system in order to achieve a goal. The actor can be human or an external system. The use case is made up of a set of possible sequences of interactions between systems and users in a particular environment and related to a particular goal. It consists of a group of elements (for example, classes and interfaces) that can be used together in a way that will have an effect larger than the sum of the separate elements combined. The use case should contain all system activities that have significance to the users. A use case can be thought of as a collection of possible scenarios related to a particular goal, indeed, the use case and goal are sometimes considered to be synonymous.

We started to create small approaches to understand the use case diagrams.

Bellow we will demonstrate a possible Use Case Diagram for Cozy Photos.

![Use Case](https://github.com/Mosaal/cozy-photos/blob/master/ESOF/2nd-Report/Cozy.bmp?raw=true "Use Case")

In this version of the Use Case Diagram we consider the Boundary as the Application running on the Servers
The Actors are everything that can interact with that Application.
And the Use Cases are the actions that the Actors are able to perform in order to interact with the Boundary.

Use cases like Register in the Application Database is done by Actors like Users, Moderators and Admins. 
Actions like Login and Logout are performed by the same three Actors as well. Although, in order to perform actions like Login, it may be necessary to Register. Logout action requiers the User to previous Login in the Platform.
Every User Interaction requires a previous Login.
A user is able to Create their Personal Account, done while Registering, and he is free to Update or Delete it.
The Photos are upload to Albums. So the User once again is able to Create or Delete Albuns.
The User, upon Uploading a Photo to an album, an oher actor comes in place. The Smartphone or Computer Provides the Photo intended to be uploaded. 
The same happens when the User wants to share a Photo, the Email Service will be called and Send Email to share the Photos.
The Moderator is able to provide Support for troubling issues.
And finally the Admin can manage every User Account, Album and Photo Properties. As well as being able to Delete an Accout, Albuns and Photos of each User registered in the platform.

## Domain Model
Domain modeling is a way to describe and represent real world individuals and the relationship between them. 
These relationships and individuals describe the problem domain space.
Domain modeling is one of the key models used in software engineering.
Unlike User Models, Domain Models have external actors, tansient data, classes without data, etc.

Bellow we will demonstrate a possible Domain Model Diagram for Cozy Photos.

![Domain Model](https://github.com/Mosaal/cozy-photos/blob/master/ESOF/2nd-Report/Domain%20Model.png)

As we can see an User can delete and share Albums that he creates, as well as the Photos that are contained in those Albums.
Photos which are uploaded by the very same User.

## Topics Covered by Student
- Alexandre Moreira (Domain Model)
- João Lemos (Outside Development; Requirements: Introduction, Purpose/Scope, and Description; Use Cases Introduction; Domain Model Introduction)
- Mariana Guimarães (Specific Requirements and Features; Outside Development)
- Nuno Neto (Use Cases)

## Members and Contacts
- Alexandre Moreira (up201303281@fe.up.pt)
- João Lemos (ee10201@fe.up.pt)
- Nuno Neto (up201406003@fe.up.pt)
- Mariana Guimarães (up201307777@fe.up.pt)

## Credits
All the credits go to the owners and creators of [Cozy Photos](https://github.com/cozy/cozy-photos).
