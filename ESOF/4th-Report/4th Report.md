# 4th Report

## Discuss Software Testability and Reviews
The Software Verification and Validation step is of extreme importace in software engineering. From providing multiple case tests and ensuring the safety and coherence of our system we are able to provide a favorable and safe experencie. Sometimes even saving human lives!

In this part of the Assignment we will discuss a bit about Softwares Validation and Verification.

It is true that the system we are studying is really complex and big. Solving a problem or a bug may need requiere unplanned funds to proceed. So how do we control the existence of problems/bugs? How do we optimize review time? 

The problems in Verification are not about the lack of methods. There are many ways to proceed a project Verification. Most times depends on the reviewer. The reviewer must always try to find the methods he is most familiarized with. Altough in some cases it is a team that will perform the verification, in this situation the team must discuss which methods must be used.
Both cases depend on the context of the project or in some cases it depends on the internal functioning of the team. Or even both!

A way to review code is for example through checklists. A checklist helps make the review more effective and efficient, by focusing
the attention on the most frequent and important problems. In the contex of this project it might help in individual reviewing. 

Another way to review code is using peer to peer review or even intercalated peer to peer between a team. This methods consist in exchanging code or/and reviews between programmers. This helps checking errors more quickly. Of course that for this there must be good and efficient communication. And for that each coder must guarantee that his work is easily reviewable. Improving efficiency naturally.
This methods not only optimize time but it also help to control and to observe the overhall state of the project, leading to a more reasonable and organized system.

We have no information regarding any code review technic used by the cozy team. But we are sure there were some technics used given the complexity of the system developed. 
 
Now that we have talked about verification it is time to discuss validation! So, how do we know if the system is valid? Does the final product fulfills all the expected requierments? How do we ensure the quality of the final project? 
 
Validation of a product is mainly done through test cases. In some cases very specific test cases. 
In fact the validation can be done in different phases: 
 
- Unit Testing (individual hardware or software units) 
- Integration Testing (testing sotware or hardware nodes combined) 
- System Testing (tests on the complete integration of the system) 
- Acceptance Testing (customer pre-release testing) 
- Regression Testing (evaluate the results)

Each phase require different test types. And each test has different types too. 
Tests can be a Black Box test (according to external specification) or White Box test (according to program structure).

Of course that in some projects some tests might not be executed. It depends mostly on the project desgin and the initial requirements. 
In the case of the Cozy team it is crucial to follow a good validation plan. The project, given its complexity, can become very hard to validate and keep updated. That is why a good planing for Verifications and Validations are required. 

A way to use good Validation and Verification is to create an intial stable release. Of course this one is not final, and it will suffer innumerable updates throught the system life time. But this updates most of the times are reports from external individuals or groups of people. This is a huge advantage having an open source project or a Alpha/Beta release. 
Cozy used this method and it is proving itselft to be great for the project. Multiple people report problems and bugs everyday and everyday external people provide solutions for those problems. 

Dispite being only a good way to give feedback and getting free voluteer help it also really improves efficiency, optimizitation, verification and validation.
Getting external help is so important for the Cozy Team that since the beggining, they provided a small mentoring support section for those who wish to help by getting their hands "dirty" trying to create a better and stable version of the System. 
Also their github section has a "bug" and "enhancent" section for those who find possible bugs and future enhancments for the project (not only on Github but also on their own discussion forum: https://forum.cozy.io/).

Bellow we will try to describe how it is possible to help the team, solve a problem/bug, improve the project, describe the steps to install their development enviorment, create and run tests, record the tests coverage and finally we will take a small bug reported on their forum, describe it, and show how it is a bug in the system given the intial planning and requirements specifications. 

## Report Test Statistics and Analytics
In order to be able to report the results of the different tests associated with the platform we had to, first of all, set up a development environment. The environment itself is made up of two parts: an easy-to-use Virtual Machine and a local Node.js tool called `cozy-dev`. In order to have everything up and running you must follow the following steps:

1. Install [Git](https://git-scm.com)
2. Install [Node.js](https://nodejs.org/en/)
3. Install [VirtualBox](https://www.virtualbox.org) and [Vagrant](https://www.vagrantup.com)
4. Install `cozy-dev`

  * `cozy-dev` is a set of tools aiming to help you managing your app deployment and your development environment. It is recommended to install it system-wide. How? `sudo npm install -g cozy-dev`. In the Windows operating system you don't use the command `sudo`, that is only for a GNU/Linux system or Mac OSX.

5. Download and Start the environment

```
# Create a development directory
mkdir cozy && cd cozy

# Download the environment
cozy-dev vm:init

# Start the environment
cozy-dev vm:start

# Check that the environment is properly started
cozy-dev vm:status

# Update the environment (strongly recommended)
cozy-dev vm:update
```

Once you have everything set up you can start hacking the Cozy Photos app. In order to do so follow these instructions:

`git clone https://github.com/cozy/cozy-photos.git`

Run it with

`node server.js`

Each modification of the server requires a new build

`cake build`

Each modification of the client requires a specific build too

```
cd client
brunch build
```

To run tests type the following command into the Cozy Photos folder

`cake tests`

## Identify and/or correct a bug

## Topics Covered by Student
- Alexandre Moreira (Report Test Statistics and Analytics)
- Nuno Neto (Discuss Software Testability and Reviews)
- Mariana Guimarães (Report Test Statistics and Analytics)

## Members and Contacts
- Alexandre Moreira (up201303281@fe.up.pt)
- João Lemos (ee10201@fe.up.pt)
- Nuno Neto (up201406003@fe.up.pt)
- Mariana Guimarães (up201307777@fe.up.pt)

## Credits
All the credits go to the owners and creators of [Cozy Photos](https://github.com/cozy/cozy-photos).
