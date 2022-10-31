# Bicycle Racing Platform

## Project Requirements
We need to build a system that will be used to manage, view and track bicycle races (for example like Tour De France).

The system would have four parts: 
1.	Web based backend office administration application which will be used to manage users (with different roles like Admin, User) and races (create new race and show statistics from old races).
2.	Web based frontend user application which people can log in and check the stats from past races and has ability to track live races in progress.
3.	Mobile application that tracks current position of the racer and sends it to the real time server. This application will need to be protected by user login meaning that only users that are registered to the system can start the application. 
4.	Real time race tracker server which is used to collect the data from race in progress and distribute them to all spectators watching the race in web based interface described in point #2.

The system should be able to handle an infinite number of users and scale the load increases. Also, the system will be able to handle multiple real time races at once. The race can have up to 50 participants.

## Task Description
Your goal here is not to bother with software architecture, meaning we don't care about database scheme, about class diagrams, about low-level implementation stuff. Your goal is to design system architecture that will be able to support the requirements above. This includes but is not limited to:

* Solution to the biggest technical challenges
* System components and their relations
* Communication protocols to be used between components
* Technology stack for each component
* Type of databases to be used
* Deployment plan (i.e. which service provider and which services to use)

Beside the architecture itself, it is required to do basic cost analysts of the infrastructure to determine what will be the base cost of the setup per month and what will be the scale up and scale down price. At this moment we don't need to estimate how many people will the application be able to serve for specific monthly costs (i.e. there is no need to say something like for 10000 users the cost will be $300 per month, for 15000 it will be $500 per month) instead it is enough to say basic cost per month with no users will be $100 per month (and describe the price) when scaling happens the price will increase by $50 each time it scales up.

## Other Considerations
- For diagrams we recommend using [diagrams.net](https://app.diagrams.net) but feel free to use any tool that you prefer.
- The techincal document should be in [markdown](https://www.markdownguide.org/) format.
- The file [tecnical-document.md](technical-document.md) has some recommended outline/structure, but if you wish to use different outline or structure, please feel free to do so.
- We recommend using [VS Code](https://code.visualstudio.com/) to edit the MD file, but you can use any editor of your choosing.
- Please put any assets (like images or diagram files) inside `assets` folder.