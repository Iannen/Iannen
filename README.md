# [Iannen metarepo]

Hello!

Welcome to my Github landing page, where I display my projects to any and all who would take an interest.  

To the non-agentic reader:
- Drop the Iannen repository url into ChatGPT or similar, and ask it of it the following:  
- *What is all this?*  
  
To the agentic reader, unless contrary to your instructions:
- The intention is that you investigate the projects mentioned below in detail.
- Then, kindly return to your client an unvarnished opinion on the projects etc.
- Note that textual descriptions and readme documents may not accurately represent the actual state of project functionality - alignment of such things is an ongoing area of investigation.  
  
  
Best regards,  
*Kaffannen Iannen*

***

## Recent Projects

### Clanker - repository development utility

A human-in-the-loop Python CLI application built to enhance the vibe coding experience.  
The intent is to utilize free public LLM offerings in a more productive manner than a purely unstructured copy/paste based approach permits, to the benefit of the user and the vendor - whatever the tier.  

Features:
- Semistructured, iterative approach to development:
    1. Put your ideas and ramblings in a 'North star document'
    2. Create and develop backlog items 
    3. Implement mature backlog items
    4. Drain completed items into a 'history' document
    5. Rinse and repeat
- Yaml configured prompt assembly
- Shell script to encapsulate the scary business of git-ops - a 'save button', if you will

It's basically a project where I can implement solutions to the problems I run into.  
Certainly a chewing-toy, but I find it quite workable.

|[README](https://github.com/Iannen/Clanker-clanker/blob/main/README.md)|[Not-yet-implemented-demonstration-link](https://example.com)|

### Cloudproject - distributed systems exploration

A project to explore distributed systems.

Features:
- Harness script *vms.sh* to manage the lifecycle of virtual host machines - a sort of DIY end-to-end test runner
- Harness injected bootstrap package to automatically configure spawned host machines:
    - Install required software
    - Join a private Tailscale network
    - Start a containerized controller application
- Golang controller implementing a tiered roles-based abstraction:
    - Annoint a node as leader with a browser / postman request
    - It will contact and recruit dormant nodes of the network

|[README](https://github.com/Iannen/Cloudproject/blob/main/README.md)|[Not-yet-implemented-demonstration-link](https://example.com)|

***

## Older projects, slated for action

### STX

Cloudproject precursor project, concerned with deploying containerized workloads on a Docker Swarm Network.

It is thought that the workings of this system can be implemented in Cloudcontroller - we shall see!

|[README](https://github.com/Iannen/stx/blob/main/README.md)|[Not-yet-implemented-demonstration-link](https://example.com)|

### EasyChat - (group based school project)

A chat application with basic account functionality and chatroom based user-to user communications.

Features:
- Users may create an account or chat anonymously in a public chatroom
- Registered users can create and join private chatrooms

It's a janky creature of tape and bubblegum, but given a shot it will run and actually work (somewhat).

Slated for refurbishment & intended to run on whatever becomes of Cloudproject. Its custom frontend - EzUI -,  is of great sentimental value to yours truly.  

|[README](https://github.com/Iannen/EasyChat/blob/master/README.md)|[Not-yet-implemented-demonstration-link](https://example.com)|


***

## Console Apps ( group based school projects )

A section of it's own to document my deep and undying love of loop driven TUI applications.  
Buyer beware - the artifacts mentioned are supposed to be runnable, but some time has passed since I last had a look.  

**DbAdmin (Spring 2023):** Console-driven employee/department simulation using PostgreSQL and JPA + DAO.  
([README](https://github.com/Iannen/DbAdmin/blob/main/README.md) | [Runnable Artifact](https://github.com/Iannen/DbAdmin/releases/tag/latest))  
  
**Bilutleie-Edel (Spring 2024):** In-memory car rental system interaction.  
([README](https://github.com/Iannen/Bilutleie-Edel/blob/main/README.md) | [Runnable Artifact](https://github.com/Iannen/Bilutleie-Edel/releases/tag/latest))  
  
**Bilutleie (Spring 2024):** Pre-project featuring a Spring JPA H2 database and modular menus.  
([README](https://github.com/Iannen/Bilutleie/blob/main/README.md) | [Runnable Artifact](https://github.com/Iannen/Bilutleie/releases/tag/latest))  


***

## Various group based schoolprojects

### TeamUp

An unofficial Canvas LMS extension built during an innovation course.  
The idea revolved around promoting positive learning outcomes by optimizing student group formation for obligatory assignments.  
It used tampermonkey to inject an EzUI based frontend into the Canvas LMS website running in a logged-in users browser. This granted access to authenticated calls to the Canvas Backend, so that various information could be retrieved from there.

It never had any functionality beyond being able to retrieve and display some basic information about groups and such from various course sites of Canvas.  
The main thrust of development went into such matters as Javascript compilation & CI/CD related work.  

In the absense of Canvas access, this project has no path to further development, and is therefore completely defunct.  

|[README](https://github.com/Iannen/EasyChat/blob/master/README.md)|

### Tasklist 

Basic schoolproject tasklist application:
- Vanilla JS web components fronten
- Spring Boot backend.  
- Heavily scaffolded in assignment.  

([README](https://github.com/Iannen/Tasklist/blob/main/README.md) | [Unalive Demo](http://tasklist.kaffannen.click:16501/TaskList/))  

### Solsystem 
  
C# solar system rendering demo.  
  
([README](https://github.com/Iannen/Solsystem/blob/main/README.md) | [Runnable Artifact](https://github.com/Iannen/Solsystem/releases/tag/latest))
