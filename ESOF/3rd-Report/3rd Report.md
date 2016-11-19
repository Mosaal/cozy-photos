# 3rd Report
## Introduction to Software Architecture and the 4+1 Architectural View Model

## Logical View
Covered by João

## Development View
Covered by Alexandre

## Deployment View
The Deployment View is able to show hardware nodes, communication relationships and software artifacts deployed on them.
This helps to have a wider view about the system being studied.
Bellow we show a example of a Deployment View.

![Deployment View](https://github.com/Mosaal/cozy-photos/blob/master/ESOF/3rd-Report/deployment.bmp?raw=true "Deployment View")

## Process View

Process view shows processing steps, data/object stores, data/object-flows, and opportunities for parallelization.
Covered by Mariana

## Architectural Design

We were able to identify a very distinct Design Patern in cozy Photos.
Given that the platform works mostly with the server and client platforms, it is obvious that the developers based their work in a Client-Server Architecure.

The Client-Sever approach consists on a distributed system in which the client requests services from servers through a shared netword or middleware. What this means is that behind all the applications and distributions for different platforms provided to the client, there is a huge service manager that gives all the features to the client platforms and connects different clients through it. In this case is the Cozy Server. Dispite the fact that we are not studying the server itself and even if the Cozy Photos platform has another more internal architectural design. The application itselt consists on multiple server requests which is why we believe the Cozy Photos platform was initially designed having in mind the server itself.

Bellow we show a small concept of Cozy Photos and Cozy Server connections:

![Client Server Approach](https://github.com/Mosaal/cozy-photos/blob/master/ESOF/3rd-Report/client-server.png?raw=true "Client Server Approach")

## Topics Covered by Student
- Nuno Neto (Deployment View, Architectural Design)
- Mariana Guimarães (Process View)

## Members and Contacts
- Alexandre Moreira (up201303281@fe.up.pt)
- João Lemos (ee10201@fe.up.pt)
- Nuno Neto (up201406003@fe.up.pt)
- Mariana Guimarães (up201307777@fe.up.pt)

## Credits
All the credits go to the owners and creators of [Cozy Photos](https://github.com/cozy/cozy-photos).
