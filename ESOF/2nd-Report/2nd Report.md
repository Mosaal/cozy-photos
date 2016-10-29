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
* Why is the system necessary

This is how Requirements are used on order to develop a project that goes side by side to the clients' and users' ideology making sure that they get what they need.

Next we will take a look at how Requirements took part in the development of Cozy-Photos. A message has been posted in their foruns and a response is beeing waited.

## Specific Requirements and Features
Forum post waiting response
https://forum.cozy.io/t/requirement-elicitation-report/3656/1
- Alexandre e Mariana

### Outside Development
As stated in their website, the Cozy developers clearly instate that they intend for cozy to also work as a web development learning tool. 
This way they allow for users who whish to develop to reuse the data already stored in the Cozy, they also want users to take the code apart, study it and "hack it to your heart's content." 
By allowing data reuse they what people to build new services on top of the user's data. The user's developed apps can then be introduced to the Cozy communityso that feedback is given and the product improved. 
But nowere is it stated that the "external projects" can enter the main app functions. 
A question about this has been sent to the developers.

Besides having open source code and insisting on having users "toying" with their code deveoping for themselves Cozy also has a mentorship program to help building personal apps. 
Topics covered by the mentorship are: code training, debugging or improving the design of user's apps. Cozy is a perfect platform for learning Node.js, Express.js, React.js and Angular JS and how these frameworks are used in real-word software development.

To those not adept in the programming department cozy offers a lot of ways to help with the project. They ask for anyone that can to translate de applications and documentation, to test the app on all the avaiable devices, answer forum questionnaires, try to replicate 
issues reported by other users, write tutorials and release notes, improve doccumentation, among other available options.

## Use Cases
“A use case is a sequence of transactions in a system whose task is to yield a measurable value to an individual actor of the system”

A use case is a list of actions/steps, defining the interactions between a role and a system in order to achieve a goal. The actor can be human or an external system. The use case is made up of a set of possible sequences of interactions between systems and users in a particular environment and related to a particular goal. It consists of a group of elements (for example, classes and interfaces) that can be used together in a way that will have an effect larger than the sum of the separate elements combined. The use case should contain all system activities that have significance to the users. A use case can be thought of as a collection of possible scenarios related to a particular goal, indeed, the use case and goal are sometimes considered to be synonymous.

We started to create small approaches to understand the use Case diagrams.
Actors being User, Admins and Moderators.
Machines being Server and Application

Bellow we will demonstrate a possible Use case Diagram for Cozy Photos.
This diagram is based on the real system architecture posted in the following link: https://cozy.io/en/architecture/

![Alt Text](https://github.com/Mosaal/cozy-photos/blob/master/ESOF/2nd-Report/Use%20Case.png?raw=true "Use Case")

## Domain Model
Domain modeling is a way to describe and represent real world individuals and the relationship between them. 
These relationships and individuals describe the problem domain space.
Domain modeling is one of the key models used in software engineering.
Unlike User Models, Domain Models have external actors, tansient data, classes without data, etc.

# Topics Covered by Student
- Alexandre Moreira (Specific Requirements and Features; Domain Model)
- João Lemos (Outside Development; Post on forum; Requirements: Introduction, Purpose/Scope, and Description; Use Cases Introduction; Domain Model Introduction)

## Members and Contacts
- Alexandre Moreira (up201303281@fe.up.pt)
- João Lemos (ee10201@fe.up.pt)
- Nuno Neto (up201406003@fe.up.pt)
- Mariana Guimarães (up201307777@fe.up.pt)

## Credits
All the credits go to the owners and creators of [Cozy Photos](https://github.com/cozy/cozy-photos).
