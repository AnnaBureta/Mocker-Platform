DEVELOPER’S GUIDE TO THE MOCKER PLATFORM

Mocker allows you to build, package, and deploy applications.
BASIC TERMS 
APP CONTAINERS	A Mocker container is a bundle of software, libraries and configuration files. It can run on any cloud infrastructure.

MOCKER IMAGES	Mocker containers are based on templates called images. You can run a Mocker image in parallel in as many containers as necessary.
To create a Mocker image, you need to:
•	know javascript
•	have a basic understanding of app containers. 
	If you are less familiar with app containers, you can start using our configuration templates.

MOCKERFILES	Each Mocker image is defined in a Mockerfile. Mockerfile is a text file defining the location of the resources needed by the Mocker container. 
When you create a container from a Mocker image, all the resources are bundled and run on a virtual machine dedicated to that Mocker container.

MOCKER DAEMON	The Mocker daemon runs and manages containers on a software virtualization platform in the cloud.

HOW TO DEPLOY MICROSERVICES:
	Prerequisites:
1.	You know the structure of Mockerfiles
2.	You know the API of the Mocker daemon
Step by step:
1.	Install the Mocker daemon
2.	Do you have access to the Mocker administrator tools (paid service)?

YES						
You can deploy Mocker containers straight away

NO
a. Create your own scripts to control the Mocker daemon
b. Manage the initialization and shutdown of containers
	 


Important!
The Mocker administrator tools are optimized for Amazon cloud services. They enable rapid deployment of Mocker containers without the need of additional scripting. 
	Not familiar with Amazon web services? You can read our extensive documentation.


THE MOCKER PLATFORM - FAQ

What is Mocker?
Mocker is a software packaging platform. Developers can use it to build, package and deploy applications. 

How does it work?
Mocker is based on app containers. Mocker containers consist of software, libraries, and configuration files. Mocker infrastructure uses only as many containers as needed at a given point in time.

What do you pay for?
Mocker is a Platform-as-a-Service product. The core technology is open source. Customers pay for: 
•	the number of Mocker containers run at a given point in time
•	access to support and administrator tools (optionally)

Why would I need administrator tools?
They enable rapid deployment of Mocker containers. You won’t need to do any additional scripting. They save your time and energy.

What if I don’t want to pay for administrator tools?
Cost optimization will be more difficult because you will have to:
•	create your own scripts to control the Mocker daemon
•	manage the initialization and shutdown of containers

What is the Mocker daemon?
The Mocker daemon runs and manages containers on a software virtualization platform in the cloud.

Does Mocker work on any cloud infrastructure?
Yes. Containers can run on any cloud infrastructure, but the Mocker administrator tools are optimized for Amazon cloud services. 


