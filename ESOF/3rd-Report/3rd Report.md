# 3rd Report
## Introduction to Software Architecture and the 4+1 Architectural View Model
4+1 is a view model designed for
> describing the architecture of software-intensive systems, based on the use of multiple, concurrent views
The views are used to describe the system from the viewpoint of different stakeholders, such as end-users, developers and project managers. The four views of the model are logical, development, deployment and process view. In addition selected use cases or scenarios are used to illustrate the architecture serving as the 'plus one' view. Hence the model contains 4+1 views:

## Logical View
This view focuses on realizing an application’s functionality in terms of structural elements, key abstractions and mechanisms, separation of concerns and distribution of responsibilities. Architects use this view for functional analysis.

The logical architecture is represented at different levels of abstraction and progressively evolves in iterations.

1. Vertical and horizontal divisions
 The application can be vertically divided into significant functional areas (i.e.,order capture subsystems, order processing subsystems).Or, it can be horizontally divided into a layered architecture distributingresponsibilities among these layers (i.e., presentation layers, services layers, business logic layers, and data access layers).

2. Representation of structural elements as classes or objects and their relationships

![Deploy View](https://github.com/Mosaal/cozy-photos/blob/master/ESOF/3rd-Report/lgv.jpg)

## Development View
The development view illustrates a system from a programmer's perspective and is concerned with software management. It uses the UML Component diagram to describe system components. This view depicts how components are wired together to form larger components or software systems. They are used to illustrate the structure of arbitrarily complex systems.

Below we show an example of a Development View.

![Development View](https://github.com/Mosaal/cozy-photos/blob/master/ESOF/3rd-Report/ComponentView.png)

## Deployment View
The Deployment View is able to show hardware nodes, communication relationships and software artifacts deployed on them.
This helps to have a wider view about the system being studied.
Bellow we show a example of a Deployment View.

![Deployment View](https://github.com/Mosaal/cozy-photos/blob/master/ESOF/3rd-Report/deployment.bmp?raw=true "Deployment View")

The Deployment View for cozy photos is not very complex. There is a server that allows multiple users to request server services.
All the artifacts depenendencies and architecture are described in the other diagrams. 
A client node can be a Smartphone or a Personal Computer.
On the server node the main artifact is the 'server.js' which uses and calls functionalities from all the other listed artifacts. That is why they are all listed as server artifacts. Some artifacts have a relative path. This is because some artifacts names are similar between them and so they can not be in the same path as the 'server.js' although they provide different functionallity.
On the client node the main artifact is the 'client.js' artifact. This artifact calls fuctionalities from other artifacts in execution time. That is why they have to be be in de diagram as well. Packages, dependencies and connections information about the artifacts deployed in the nodes are discribed in the other diagrams.

## Process View

Process view shows processing steps, data/object stores, data/object-flows, and opportunities for parallelization.
Covered by Mariana

## Architectural Design

We were able to identify a very distinct Design Patern in cozy Photos.
Given that the platform works mostly with the server and client platforms, it is obvious that the developers based their work in a Client-Server Architecure.

The Client-Sever approach consists on a distributed system in which the client requests services from servers through a shared netword or middleware. What this means is that behind all the applications and distributions for different platforms provided to the client, there is a huge service manager that gives all the features to the client platforms and connects different clients through it. In this case is the Cozy Server. Dispite the fact that we are not studying the server itself and even if the Cozy Photos platform has another more internal architectural design. The application itselt consists on multiple server requests which is why we believe the Cozy Photos platform was initially designed having in mind the server itself.

Bellow we show a small concept of Cozy Photos and Cozy Server connections, were the left side shows the application Cozy Photos running on different platforms and on the rigth side the Cozy Server were the services for Cozy Photos are stored and processed.

![Client Server Approach](https://github.com/Mosaal/cozy-photos/blob/master/ESOF/3rd-Report/client-server.png?raw=true "Client Server Approach")

## Topics Covered by Student
- Alexandre Moreira (Introduction to Software Architecture and the 4+1 Architectural View Model; Development View)
- Nuno Neto (Deployment View, Architectural Design)
- Mariana Guimarães (Process View)
- João Lemos (Logical View) 

## Members and Contacts
- Alexandre Moreira (up201303281@fe.up.pt)
- João Lemos (ee10201@fe.up.pt)
- Nuno Neto (up201406003@fe.up.pt)
- Mariana Guimarães (up201307777@fe.up.pt)

## Credits
All the credits go to the owners and creators of [Cozy Photos](https://github.com/cozy/cozy-photos).
