
--------------------------------------------------------------------
IMPLEMENTING WEB TRANSACTION SYSTEMS: STEP BY STEP
By Anoop M.

anoopj12@yahoo.com
http://www.xtserver.com/anoopvision

11:11 AM 2/18/01

--------------------------------------------------------------------

Dear User,

This project is basically to demonstrate an ASP Based transaction system. That is, you will learn how to implement Winsock transactions in ASP.

You can use this component not just for implementing ECommerce transactions - but for any kind of socket based communication. Once you learn this project, you will get the concept for developing and implementing a number of features/technologies - like SMS, Chat Systems, Interaction with third party gateways, Instant Messengers etc.

This consists of three sections.

1) A COM DLL For wrapping Winsock Functionality.
2) An ASP file to test the component.
3) A Simple server to test the working of the system.

Each project is explained step by step, and the coding style is very simple with full of comments, so that even a very beginner can understand it with out Fuss or Frills.
 
 
A. THE ARCHITECTURE 
----------------------------------------------------- 
 
 
We will develop the component as a COM DLL. As you know, later, we can create instances of this socket component from ASP pages, to send and receive data. The project package with this article contains: 
SockObject - A well explained COM DLL, which shows you how to create a Wrapper class for using Sockets. 
Test Server - A standard EXE server for testing the functionality of SockObject, and for giving you the concept of writing a server. Very simple and well commented. It just echoes the data comes to it. 
An ASP file - A file named default.asp, for calling the SockObject to communicate with the server. 
Please note these projects are interdependent. In our ASP file, we will:

Create an instance of the SockObject in the ASP file. 
Sends the data to the Test Server, to get the reply. 
Destroy the SockObject. 
 
 
B. CONFIGURING THE PROJECT 
----------------------------------------------------- 
 
To make the project up and running: 

Remember that you need IIS or PWS in your system, to test the system.
Kindly go through these steps.

1) Copy the default.asp file in the with this project, to any comfortable directory in the web root (for example, if the installation path of your web server is c:\inetpub\wwwroot, create a directory MYDIR there and copy the default.asp file to c:\inetpub\wwwroot\MYDIR).

2) Open and run the SockObject project in Visual Basic 

3) Open and run the Test Server project in Visual Basic 

4) Type the URL to the default.asp file. (eg: http://localhost/mydir/default.asp)


C. A LITTLE HELP FROM YOU?
----------------------------------------------------- 

I would like to request a little help from you, just if you have any option to provide it to me.

I recently developed a website that enables established training companies working in the field of Certification Training, and now I'm planning to sell out the site to established firms/organizations. Are you in touch with any such firms/organizations? Or if you are interested in a possible business tie-up with me, for finding a potential client to market it?

Visit the site demo at http://www.xtserver.com/anoopvision/ehzone , for viewing the site. Anyway, before going to the site, see the usage guide to understand the features of this site. 

You can reach the usage guide at 

http://www.xtserver.com/anoopvision/ehzone/guide.htm

Contact me if you are interested or if you can provide any help to me.

Anyway, Thanks in advance
----------------------------------------------------- 


Sincerely
Anoop M

================================================
Anoop M
Software Architect/Web Strategist

"The proof is in doing it"

anoopj12@yahoo.com
http://www.xtserver.com/anoopvision
================================================
