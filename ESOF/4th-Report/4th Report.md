# 4th Report

## Discuss Software Testability and Reviews
The Software Verification and Validation step is of extreme importace in software engineering. From providing multiple case tests and ensuring the safety and coherence of our system we are able to provide a favorable and safe experencie. Sometimes even saving human lives!

In this part of the Assignment we will discuss a bit about Softwares Validation and Verification.

It is true that the system we are studying is really complex and big. Solving a problem or a bug may need requiere unplanned funds to proceed. So how do we control the existence of problems/bugs? How do we optimize review time? 

The problems in Verification are not about the lack of methods. There are many ways to proceed a project Verification. Most times depends on the reviewr. The reviewer must always try to see which methods he is most familiarized with. Altough in some cases it is a team that will perform the verification, in this situation the team must discuss which methods must be used, because in some cases it depends on the context of the project or in some cases in depends on the internal functioning of the team. Or even both!

A way to review code is for example through checklists. A checklist helps make the review more effective and efficient, by focusing
the attention on the most frequent and important problems. In the contex of this project it might help in individual reviewing. 

Another way to review code is using peer to perr review or even intercalated peer to peer between a team. This methods consist in exchanging code or/and reviews between programmers. This helps checking errors more quickly. Of course that for this there must be good an efficient communication. And for that each coder must check that if their work is easily reviewable. Improving efficience naturally.
This methods not only optimize time but it also helps to control and to observe the overhall state of the project, leading to a more reasonable and organized system.

## Report Test Statistics and Analytics
In order to be able to report the results of the different tests associated with the platform we had to, first of all, set up a development environment. The environment itself is made up of two parts: an easy-to-use Virtual Machine and a local Node.js tool called `cozy-dev`. In order to have everything up and running you must follow the following steps:

1. Install [Git](https://git-scm.com)
2. Install [Node.js](https://nodejs.org/en/)
3. Install [VirtualBox](https://www.virtualbox.org) and [Vagrant](https://www.vagrantup.com)
4. Install `cozy-dev`

⋅⋅* `cozy-dev` is a set of tools aiming to help you managing your app deployment and your development environment. It is recommended to install it system-wide. How? `sudo npm install -g cozy-dev`. In the Windows operating system you don't use the command `sudo`, that is only for a GNU/Linux system or Mac OSX.

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
