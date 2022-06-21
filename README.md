
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-Feb-2022** 
## Introduction to Linux & Installing Ubuntu

Linux is an open-source operating system like other operating systems such as Microsoft Windows, Apple Mac OS, iOS, Google android, etc. An operating system is a software that enables the communication between computer hardware and software. It conveys input to get processed by the processor and brings output to the hardware to display it. This is the basic function of an operating system.

- Download the linux distribution of your choice.
- Creating Boot pendrive using rufus.exe in windows.
- Restart the system and open boot menu using boot key. (Eg.- F8, F2 etc.)
- Select your boot device in boot menu.
- Select Install Ubuntu then Click Noraml Installation.
- Select where to install alongside window or Erase disk or something else.
- Then Click next and start ubuntu installation.
- For More detail about Installation Guide [Click here](https://phoenixnap.com/kb/install-ubuntu-20-04)
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 2-Feb-2022** 
## Introduction to LAMP Stack

The LAMP stack is a popular open-source solution stack used primarily in web development.LAMP consists of four components necessary to establish a fully functional web development environment. The first letters of the components' names make up the LAMP acronym:

- Linux is an operating system used to run the rest of the components.
- Apache HTTP Server is a web server software used to serve static web pages.
- MySQL is a relational database management system used for creating and managing web databases, but also for data warehousing, application logging, e-commerce, etc.
- PHP, Perl, and Python are programming languages are used to create web applications.
- Installing lamp on Ubuntu System.
- Verifying by run LAMP on localhost.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 3-Feb-2022**
## Introduction to frappe

Frappe, pronounced fra-pay, is a full stack, batteries-included, web framework written in Python and Javascript with MariaDB as the database. It is the framework which powers ERPNext, is pretty generic and can be used to build database driven apps.
**Why Frappe?
The key difference in Frappe compared to other frameworks is that meta-data is also treated as data. This enables you to build front-ends very easily. We believe in a monolithic architecture, so Frappe comes with almost everything you need to build a modern web application. It has a full featured Admin UI called the Desk that handles forms, navigation, lists, menus, permissions, file attachment and much more out of the box.

- Install Frappe-bench and its required tool. For more info [Click here](https://frappeframework.com/docs/v13/user/en/installation).
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 4-Feb-2022**
## Creating App and Site & run on local server in Frappe

- Start Bench in one Terminal.
- In Second Terminal.
- Creating App by using **bench new-app library_management** inside Frappe-bench Directory.
- Creating site by using **bench new-site library.test** inside Frappe-bench Directory.
- Run Site on Localhost by using library.test custom port name.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 5-Feb-2022**
## Introduction to Github Pages

- Getting Information What is GitHub Pages.
- Create a New Repository on GitHub.
- Setting Repository as the main branch and setting a theme for GitHub pages.
"policy domain="path" rights="none" pattern="@*"- Learning about Personal access tokens for push Local Repository on GitHub.
- Learning Syntax of Markdown Language in GitHub.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date:7-Feb-2022**
## Introduction to budibase

Budibase is an all-in-one low-code platform for building, designing, and automating business apps, such as; admin panels, forms, internal tools, client portals, and more. Before Budibase, it could take developers weeks to build simple CRUD apps; with Budibase, building CRUD apps takes minutes.

Today i was on budibase and docker.Today i have installed docker successfully.......after the initialization of docker for hosting is also done.
After applying ......"sudo budi hosting --start" command i am getting some error .I am trying to resolve them.
 I follow "https://github.com/Budibase/docs/tree/master/self-hosting" .
 
 I was so frustrated bacause of this error as i was trying very hard to resolve this error i had applied number of solutions but none of them was working. While reading a book a thought came into my mind that i had applied a command before applying the above command after applying the  above command  "sudo docker-compose --env-file hosting.properties up" is applied. when its processing is finish we need to stop this so that it can deallocate all the containers that are in use. we can stop them by pressing
ctrl+c it will take one or two minute to stop them dont press any other key.
after it is done apply the command "sudo budi hosting --start"
after applying the above command i was getting the the errors
"ERROR: for bbworker  Cannot create container for service worker-service: Conflict. The container name "/bbworker" is already in use by container "bdcdda1b5119fdba49dd3b93c0b96b82dce0d875d3d9c3b3d48900d6573563da". You have to remove (or rename) that container to be able to reuse that name.

ERROR: for worker-service  Cannot create container for service worker-service: Conflict. The container name "/bbworker" is already in use by container "bdcdda1b5119fdba49dd3b93c0b96b82dce0d875d3d9c3b3d48900d6573563da". You have to remove (or rename) that container to be able to reuse that name.
Encountered errors while bringing up the project."
then apply "sudo docker rm <container name>|| true"
it will remove the container and reallocate them .
if there are more than one container allocated then reapply the same command again.
after removing them reapply "sudo budi hosting --start"
 
 I was so happy after reolving the above error :))


 
<br>
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-Feb-2022**
## Introduction to Github Pages

 Today one of my mate gave us a presentation on github.
 He explained us what is github pages and how to create a repository.
 -How to set a repository as the main branch and setting a theme for github pages.
 -How to send push and pull request in github.
"policy domain="path" rights="none" pattern="@*"- Learning about Personal access tokens for push Local Repository on GitHub.
- Learning Syntax of Markdown Language in GitHub.
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
 
**Date : 9-Feb-2022** 
## Introduction to Reveal.JS, Pandoc, Use of Markdown in Reveal.js

- What is Reveal.JS, Pandoc, Use Markdown in Reveal.js.
- Creating Presentation in Reveal.JS using Markdown only.
- Learn how to show presentation on Local machine.
- Converting .md file into .pdf file using Pandoc.
<br>

<!---------------------------------------------------------------------------------------------------------------------------->

**Date : 10-Feb-2022** 
## Introduction to Docker, Virtual Machine 

**What is Docker?**
Docker is popular virtualization software that helps its users in developing, deploying, monitoring, and running applications in a Docker Container with all their dependencies (frameworks, libraries, etc.) to run an application in an efficient and bug-free manner.Docker Containers are Light-weight, Applications run in isolation,Occupies less space, Easily portable and highly secure, Short boot-up
time.
- It can run multiple containers on a system.
- It can start multiple containers at a time on the Docker engine.
<br>

**What is Virtual Machine?**
A Virtual Machine (VM) is a compute resource that uses software instead of a physical computer to run programs and deploy apps. One or more virtual “guest” machines run on a physical “host” machine.  Each virtual machine runs its own operating system and functions separately from the other VMs, even when they are all running on the same host. This means that, for example, a virtual MacOS virtual machine can run on a physical PC.
- It can start only a single VM on a VMX.
- It can run only a limited number of VMs on a system.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 11-Feb-2022** 
## Create a CRUD app in budibase

Building apps with Budibase involves 4 simple steps:

Install Budibase - Use Budibase Cloud to get started in seconds, or self-host your apps using Docker, Kubernetes , or DigitalOcean.
Add data - You can connect to data sources like PostgreSQL, Rest APIs, MS SQL, MySQL and more, or start from scratch with Budibase's built-in database (Budibase DB, built on top of CouchDB).
Design your UI - Build beautiful, accessible user interfaces people enjoy using. Autogenerate CRUD screens from your data, or create custom screens from scratch. Use powerful components, such as tables, buttons, form inputs, to enrich your interface. Switch from light mode to dark mode with just a click.
Automate processes - In seconds, setup automations such as email alerts, Slack notifications, CRON actions, and more.

For creating CRUD app click on "https://docs.budibase.com/docs/build-a-crud-app".
 Today i am done with the installation of erpnext.
 There was a presentation by one of my mates on frappe and how to create library mangement system in frappe framework.The presentation was good.they told us about the installation steps of frappe bench and how to create LMS and pros and cons of frappe like if we have to add users or articles then its is not possible to upload in bulk we need to upload them manually one by one.and how to create app,site and how to add articles and doctypes in LMS.
 <br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 12-Feb-2022**
 ## Introduction to Selenium, Budibase
- Selenium is browser automation tool by which you can create a script which automatically done task like fill credential and click for search.
- Budibase is a development platform designed for speed and productivity. 
- With Budibase, developers no-longer experience repetition, long-dev cycles, and frustration. Instead, developers are more productive, happier, and can deliver applications they're proud of in minutes.
 today there was a presentation on salenium by kiran she showed us how to implement salenium she implemented it on guru portal where she automated the login on guru portal without manual click.
- 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 14-Feb-2022**
## Understanding the concept of budibase app 
I am currently working on budibase. Today i was reading the concept of apps that how they are created in Budibase.
I haven’t done anything extra on budibase except reading the documentation and understanding the concept of built- in apps in budibase

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 15-Feb-2022**
## Working on Job portal app in budibase
if you want to access a budibase app without login, you will need to make some "Public" screens, and browse directly to the URL for those screens.

You will also need to make sure that your public screens are only accessing tables/queries that have "Public" access. Beware that this will mean that all data in those tables will be public (if "Read" is set to Public).
And I successfully make all screens public.
I checked how all pages are created in job portal app. How it to be published.
I am currently working on budibase. Today i was reading documents related to docker so that i can find any alternatives of dockers and to find is it possible to publish app in budibase without using docker.
 
 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 17-Feb-2022**
## Working on Budibase

 Today I am working on budibase and trying to create an app i am able create all the tables and enteries in it but when i am trying to create view of pages i am getting error. I am not able to map their views.

 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 17-Feb-2022**
## Create CRUD app using MySQL in budibase
 
 Today I was trying to create crud app-MySQL but there is an error related to database . And I am reading the documentation of erpnext (education domain) and  learnt how to create students and instructors.
For creating CRUD app click on "https://docs.budibase.com/docs/build-a-crud-app".<br>


<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 18-Feb-2022**

## Working on ERPNEXT 
Today i started working on new platform erpnext it is open source, and low code or no platform. It is fun to work on a wonderful platform they provided us so much funtionality with number of modules like education domain, crm, website etc and all these are available inside a single platform and if we want to do modifications it is also possible in the erpnext :) 
 Today i am reading the documentation of erpnext to understand the education domain. Today i have created some programs and courses now i am trying to understand how to enroll students in programs and courses.


<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 19-Feb-2022**
 ## Installation of MOSH and TMUX
 Today we were working on education domain in erpnext and trying to understand the student module of education domain. Today we got to know two new tools which are really very helpful for the coders which are TMUX and MOSH. 
Mosh: Mosh is free and command-line software that is used to connect
from a client computer to a server over the Internet to run a remote
terminal. Mosh is more intelligent than SSH. While the SSH client
waits for a TCP response from the server before showing your typing,
Mosh will display your typing in real-time and even give underlined
typing predictions. The mosh program will SSH to user@host to
establish the connection. As you know, SSH may prompt the user for a
password or use public-key authentication to log in. But mosh runs the
mosh-server process (as the user) on the server machine. Mosh will run
inside your Terminals such as xterm, gnome-terminal, urxvt,
Terminal.app, iTerm, emacs, screen, or tmux.

 Tmux: Tmux is a Linux application that allows multitasking in a
terminal window. It stands for Terminal Multiplexing, and is based
around sessions. Users can start a process, switch to a new one,
detach from a running process, and reattach to a running process.

 Also we were trying to reset administartor password of erp server.
 
 <br>

 

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 21-Feb-2022**
 
 ## Working on ERPNEXT 
I am working on education domain of erpnext in this i have created programs and courses. In erpnext program means classes and courses means subjects. And i also did the enrollments of students in the programs and courses. Now i am trying to understand the studnets groups in erpnext.

 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 22-Feb-2022**
 
## Working on ERPNEXT 
Today i am working on student group which are avialble in erpnext these are like a student sections. We can create students based on courses, Acedemic term, Activity which will help us to do group actions like if we want to generate fee of a student group at a time then it will help us in that instead of generating the fee of  single single student.

 

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 23-Feb-2022**
 
 ## Structure of erpnext
Today sir has assigned the task to explore the strcuture of erpnext. I am reading the documentation and watching youtube videoes and trying to understand it:)
 Today I have learnt what is erpnext, architecture of erpnext, what is
the role of frappe in erpnext, how erpnext is different from
traditional softwares, what is doctype and field types. 
 


<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 24-Feb-2022**

## Understanding the structure of erpnext
 Today I have learnt what is erpnext, architecture of erpnext, what is the role of frappe in erpnext, how erpnext is different from
traditional softwares, what is doctype and field types. It is very interesting as i am having fun while doing this.

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 25-Feb-2022**
## Understanding the structure of erpnext
 
 Today i have learnt how we can add and delete instructor, students, courses from backend. and i am trying to understand the structure of
erpnext. It is very simple as all the doctypes in erpnext have a table with same name in the database and we can delete, insert and update enteries of all the doctypes by using basic mysql queries.
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-Feb-2022**
## Understanding the structure of erpnext

 Today i am working on erpnext structure. I am trying to understand how views, modals and controllers are generated in erpnext and how to customize them. I am reading the official documentation and watching youtube videos to understand this. It is very difficult to understand the complete structure of erpnext as it is very big platform :(  but i am doing my best to understand it.

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 28-Feb-2022**
## Basic setup of erpext on server
Today Sir has assigned me a task to do basic setup of erpnext on server. Sir gave me admin access so that i can do it on server and told me to check how one can apply for a particular program.
 For this First i created programs some with frontend and some by using import tool, Then i created courses with import tool, and successfully imported some students and instructors in the erp and assigned them programs and courses. And i am trying to understand what is cost center in erpnext.
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 01-March-2022**
## Installation of chat app on erpnext version 13
 I and vishal installed the chat app on erpnext version 13 and it is working fine. It wasn't avialable with the official erpnext v13.
 We did:-
$ bench get-app chat
$ bench --site your-site install-app chat


<!----------------------------------------------------------------------------------------------------------------------------->


**Date : 02-March-2022**
## Reading the documentation of erpnext
Today I was reading the documentation of erpnext and trying to understand the instructor section of education domain. I got to know that while creating the instrcutor first we need to create the employee and assign them a particular company and after assigning the company we can make the same employee an instructor. Then we can assign them a particular program and courses. 



<!----------------------------------------------------------------------------------------------------------------------------->
 
 **Date : 03-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
## Instructor Module
Today I was exploring the instructor and website module in erpnext . I
implemented it in erpnext on my local device. Trying to explore all the duties and roles of instructor that are present in erpnext and also i am trying to understand the website module.



<!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 04-March-2022**
## Meeting app
Today vishal and pawan gave us a presentation of meeting app. They showed us how to create custom apps in erp and how to install it onto the site. And they also showed us the code of the app and structure and files of the meeting app. 
 Working on instructure section of education module of erpnext. 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 05-March-2022**
 
## Notice Board app
Today we all created a notice board app in erpnext within 30 minutes. It was a wonderful experience as we can created such apps withiin a short time period.
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 07-March-2022**
## Basic setup for Nanakana Sahib Public School

Today I am done with the basic setup of Nankana Sahib Public
School. I have created three programs Class 1, Class 2, Class 3 and
three instructors for each class , four courses for each class, and
2-2 topics per courses, three room and other basic requirements.
I have imported data of 8 students using the data import feature in
erpnext and also tried to update the existing record which is working
fine without any issue.

<!----------------------------------------------------------------------------------------------------------------------------->
  **Date : 08-March-2022**
## Notification After Applying for a program
Today sir assigned me a task to import all the students and applicants. And if a student is applyig for any programs then after filling the web form he should get a notification for id and password creation after the submission of web form.
<!----------------------------------------------------------------------------------------------------------------------------->
 **Date : 09-March-2022**
 
## Notification After Applying for a program
I was searching that how a student can get a notification after fubmission of the web form. For this i was reading the official documentation and watching youtube videos. After Investing so much time i got to know that in the erpnext there is inbuilt notification feature and we can apply condition in notifications for when and for what we want to send notifications.

<!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 11-March-2022**
## Notification After Applying for a program
I was searching that how a student can get a notification after fubmission of the web form. For this i was reading the official documentation and watching youtube videos. After Investing so much time i got to know that in the erpnext there is inbuilt notification feature and we can apply condition in notifications for when and for what we want to send notifications.

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 12-March-2022**
 
## Notifications and student registration via form
 
Today when i was trying to add student applicant via form i am getting
error message

Title
'StudentApplicant' object has no attribute 'status'
Error

Traceback (most recent call last):
  File "apps/frappe/frappe/email/doctype/notification/notification.py",
line 407, in evaluate_alert
    if not frappe.safe_eval(alert.condition, None, context):
  File "apps/frappe/frappe/__init__.py", line 1759, in safe_eval
    return eval(code, eval_globals, eval_locals)
  File "<string>", line 1, in <module>
AttributeError: 'StudentApplicant' object has no attribute 'status'


because in the  student applicant doctype there isn't any status
trying to resolve the issue
So i added some status in the status fields in after that it was working fine.

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 14-March-2022**

## Workflow and Basic Setup Nankana Sahib Public School
Today I created a workflow for the student applicants which has some state like approved by admission manager, approved by instructor, Approved by hod. First admission checker will acept or reject the application of students if it is accepted then instructor will get a notification for the this. Next instructor will approve or reject it if it is accepted the hod will accept it or reject it. 
 
Today we all have done the basic setup again for Nankana Sahib Public School for Class 1 to Class 8 and imported students, instructors and enrolled them in programs, courses and assigned instructors to the programs. As it was very difficult for all of us to understand because there were many same enteries of two companies one of Nankana Sahib Public School and another of Guru Nanak Dev Engineering College and there were many enteries that we all have entered for testing purpose. So today we all deleted all the previous enteries to do the setup from scratch. It was very helpful for all of us as there  were some doubts of us related to program enrollment , course enrollment  and student group.

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-March-2022**

## Course Scheduling
 Today we all have implemented course scheduling via course scheduling tool , assessment plan, attendance by using attendance tool, we were also exploring the student leave application but the problem is if we have added an application for leave and also approved it but after approving if an instructor is trying to add attendance of whole class via attendence tool then it marking everyone present including students with leave application. Today we all have explored learning management system in erpnext too "https://gne11.gndec.ac.in/lms"  which is basically student interface.
I was also working on emails basically "how we can disable email must be unique" in erpnext and I have found a solution for this problem for this we have to open the doctype and to click on customize doctype and then go to email field type then click on edit in full page there is an checkbox named "Unique"  then just uncheck it.
Now I was exploring how do I can add parents in erpnext and what are the requirements and I have found that there is an option named
guardians in erpnext education module now I am working on it.


<!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 16-March-2022**
## Report Card Generation
In the erpnext education module I was trying to generate report card
for students while creating report card I am able to show the courses
and exams but not able to show the marks of students in the report
card,


<!----------------------------------------------------------------------------------------------------------------------------->
 **Date : 17-March-2022**

## Guardian Module
I was exploring guardians modules in erpnext . I have created a
guardian in education module there are two ways to create a guardian
one by creating a user first then assign that user id to the guardian
and other is we can directly create a user in the guardian doctype
then there is a button named  "invite as user" after this in both the
methods a invitation mail is sent to the user to complete their
registration or to set a password. I was following
"https://docs.erpnext.com/docs/v13/user/manual/en/education/guardian"

But in this they haven't mentioned which type of role and permissions
we need to assign to a parent user.

<!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 19-March-2022**

## Gunicorn, Socket.io, Scaffhold 
Today we got to know three new terms that are used in frappe first is 
 Gunicorn:-Gunicorn is built so many different web servers can interact with it.
It also does not really care what you used to build your web
application - as long as it can be interacted with using the WSGI
interface.Gunicorn takes care of everything which happens in-between
the web server and your web application. 
 
 Socket.io:-Socket.IO is a library that enables low-latency, bidirectional and
event-based communication between a client and a server. It is built
on top of the WebSocket protocol and provides additional guarantees
like fallback to HTTP long-polling or automatic reconnection. 
 
 Scaffhold:-Scaffolding is a meta-programming method of building database-backed
software applications. It is a technique supported by some
model-view-controller frameworks, in which the programmer may write a
specification that describes how the application database may be used.
The compiler uses this specification to generate code that the
application can use to create, read, update and delete database
entries, effectively treating the template as a "scaffold" on which to
build a more powerful application. 


<!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 21-March-2022**
## Reading the excellent reports by seniors
Today i was reading the three report that was written by our seniors.
 1.The above report is based on the language translator in which a group
is trying to understand the role of lex and parser. It was really fun
to read this report I really enjoyed reading it. The starting of the
report, the examples delivered during the presentation, and the
question answers during the presentation is really excellent.  My
favourite part of the report was someone said "You should say, I don't
know java rather than I don't like java" and also the chinese part as
this is the best way to start and to gather the attention of the
audience and to .
 2.The above report is based on the regular expressions , in the report
they have mentioned the struggles of programmers in the early times as
they did not had the laptops and personal computers.
3.This report   "An ancient art of secure communication" is based on the
encryption and decryption It was really interesting to know how
encryption was used in the ancient times the example of "shaving the
head of employee" for secure communication was very interesting and
the example of kheer and the phrases  "Adhi raat da hanera, vich taare
hi taare, mere gharo'n oat hoyi." was very intersting.

I really enjoyed reading the above reports.


<!----------------------------------------------------------------------------------------------------------------------------->
 **Date : 22-March-2022**
## Installing new Erpnext on server
First we install frappe framework then install erpnext with education domain.
 - After this we are collecting students and teachers data from Nankana Sahib Public School. - Arranging data according to doctype in erpnext. 
 
<!----------------------------------------------------------------------------------------------------------------------------->
 **Date : 23-March-2022**
## Comparing "http://103.66.206.229:8001/gne" in mobile and laptop
Today Sir told me to comapre this site in mobile view as well as in laptop view. As there was some problem in the mobile view. Also I was working on the ducation domain of erpnext and trying to understand it. 


<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-March-2022**

## Working on Leave management
Today i was trying to understand the default workflow of employee leave management system means how employee can add their leaves and how HR/Department head will get the leave notification and how they will accept the leaves. And I was exploring the types of leaves and the salary cut for the leaves.

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-March-2022**

## Helping others in their tasks
Today i Was helping others in their tasks. I 
helped Jaspreet in importing instructors as there were some issue we both were trying to resolve it and after investing some time in it it got resolved.
 After this I helped Sehjal in importing And adding the students in erpnext. And was trying to understand their tasks.
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-March-2022**
## Naming series According to the company
Today Sir assigned me and vishal  a task to change the naming series of student applicant doctype according to the company abberivation so that we can identify the students of each company(school/college) by looking at their naming series. There was a solution avialable in the official documentation of erpnext and we tried it but it wasn't working. We also tried some changes but still it wasn't working. After this we  were searching for the other solutions and there was a solution available in the discussion forum. We tried it on local machines and it was working perfectly after this we implemented it on gne11.gndec.ac.in

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-March-2022**

## Trying to understand the student leave section
Today I am trying to understand the student leave section under education domain of erpnext. I was trying to understand the default workflow of student leave section. how students will add their leaves and how instructor will get notification of the leaves.  

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 29-March-2022**
 
## Created new web-form and doctype for trainees
Today i created a doctype named trainees_details with some fields and after that i created a web form based on this doctype. after creating this i gave web view to the doctype and after this i added it on the website so that students can fill their personal information.

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 30-March-2022**
## Integration of Erpnext with moodle
 
Today sir gave me a task to find a solution to integrate erpnext with moodle.After searching i got to know a new tool by which we can integrate erpnext with moodle.Myddleware for Moodle enables you to transfer your data easily and
safely from your Moodle application to other applications such as your
e-commerce, CRM or messaging tools. By doing so, it ensures a durable
quality of your data, which is a prerequisite for productivity and
efficiency. Your company can save time and money on data issues : no
more endless IT expenses to ensure a smooth and secure data migration
process, no more worrying about lost, out of date or incorrect data.
With Myddleware, increase customer satisfaction thanks to a greater
data quality.

Myddleware, easily connect Moodle to other applications for more
productivity and efficiency :

  CRM/ERP : Salesforce, SAP CRM, SugarCRM, SuiteCRM, ERPNext, Hubspot,
Cirrus Shield
                        Manage your Moddle courses directly from your
CRM and collect information on course completion



<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 31-March-2022**
## Enabling chat options for the student users
Today Sir assigned me a task to find how we can enable chat options for studnets as they didn't have desk access or chat option. In order to enable chat access we need to give all the students desk access but very limited. I gave 2-3 students customer role with the students role then they have desk access and also chat access. 

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-April-2022**

## User Permissions
Today my task was to only show all the instructor and students only their concerned programs and courses on desk and on lms as well. I was searching for the solutions and also posted my query on discussion forum. And i got one reply for this they said to use user permission for each user and assign them particular programs and courses. After doing this instrcutors and students was able to view only their concerned programs and courses on desk. Also on Lms only the assigned programs and courses was visible to the students but to the instructors all the programs and courses was visible even after giving user permissions and role based permissions :( 

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 2-April-2022**
## Reading the files of LMS
As by using user permissions still instructor was able to see all the programs and courses. To find the solution for this we are trying to understand the structure of lms for this i was reading all the files of lms present in erpnext in the programs and course file it is metioned that by default instructor has access to all the programs and courses.

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-April-2022**
## User Permission
After applying the user permission to the instructor for programs and courses instructor is able to see there current programs only. When instructor is trying to access the courses they are able to access it. But when they are trying to access the programs they are getting error/ Notification:-
 "Not allowed for Course: Math-6 in Row 2. Restricted field: courseUser
"abc@gmail.com" (instructor)  does not have access to this document

Insufficient Permission for Program Class-6"
 Now I am trying to understand how to resolve it. Because this error means that to give access to the instructor first we need to to give access of all the courses to the instructor even if they are not teaching all the courses which is unacceptable in technical terms. 


<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 6-April-2022**
## Creating Library Management System
As per official documentation I created Library Management App.
 
 - Install app on site then creating doctype.
 - Use Features like Naming Series, Permission Rules. 
 - Learn Controller methods, Doctype Features, Form Scripts. 
 - Adding Web view for preview Articles on web.



<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 7-April-2022**
## Understanding the quiz format
Today I was searching that how can we hide the quiz result from the users and show them after some time. For that first I have checked all the quiz related doctypes and related parameters but in these there wasn't any control available for this. Then i checked all the doctypes files in erpnext folder and tried to understand the coding. In these files there isn't any condition available for the result they are showing the result based on a condition if checked question is right then show status pass, result, time taken etc else status fail and result, time taken etc.


<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 8-April-2022**
## Writing Requirement and Specifications For the Souvenir Project
Today Sir explained us all the requirements of the souvenir project and what is the required outpiut of this project. Sir also explained us the yadein project which was used to generate souvenir of all the students near about 10 years ago And all the technology used in the yadein project. I accepted the souvenir project. So sir told me to first write the requirements and specifications of the projects and to share it with the sir. 

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-April-2022**
## Acceptence of the Requirements of Souvenir
Today the requirements and specification of the souvenir project got approval form the sir :) 
 After this i immediately started working on souvenir project. Fisrt i created a doctype named souvenir with some fields like name, branch, urn, crn, dob, fathers name, mothers name etc, and there are two sections avialble for the friends Info of friend1, And Info of Friend2 in these field students will fill the details of their friends and comments for them. 
 After creating the doctype and giving it web view I created a web-form based on the souvenir doctype and the name of the webform is souvenir-form it has same field as souvenir doctype. I Did all this on my local erpnext.

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 11-April-2022**

## Souvenir on server
After successfully creating the souvenir doctype and souvneir web-form and after checking if it is working or not. Today I created the souvenir doctype and souvenir web form on gne11.gnde.ac.in. And I was also working on the education domain of erpnext for nankana sahib public school.
 

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-April-2022**

## Souvenir on Server
Today I was working on the souvenir form. On our website i wasn't able
to access the web form due to server exception.Then i created the
souvenir doctype and souvenir webform on my local erpnext system. Sir
told me to refresh the gne11.gndec.ac.in and pray sincerely :) . After
this i was able to access the web form. Now the problem is that the
user is able to attach image in the image field with login. But user
is not able to attach image in the image field  (but user is able to
select image of their choice). I also tried it on my local erpnext
system, on that i am getting same problem.


<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 13-April-2022**
## Souvenir and Basic coding guide part-1
Today I was working on souvenir web-form sir told me to add some more fields in the souvenir web form and do some changes in it.
 Also I have read the basic coding guide part-1 it was very fun to read this as i like reading they have explained each and every this in a wonderful way. This was actually a story of farmer who started his own business and wanted to integrate everything on a single platform then after Searching on internet he got to know about erpnext where he can combine all the modules like accouting, sales management, employee management.
 After the introduction they explained very well the tutorial of erpnext. 


<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-April-2022**

## Presentation of Nankana Sahib Public School Project
Today we had a meeting with Satinder Sir and a teacher from Nankana Sahib Public School. In today's meetings we all presented what we have done till now. We showed them the whole workflow to add a student. For which first we need to add a student applicant and explained that there are two methods for this one is online by using web form and another is offline after the application is accepted we can enroll them in the programs by single-2 enrollment of every student and by using the program enrollment tool and we showed them the lms interface of student how student is going to access the programs and courses and quizzes.

After student section we showed them the whole working of instructor how instructor can add content like articles, videos and quizzes in lms, mark the attendance of students etc. After Instructor we presented the HR module how to generate payrolls, salary slips, attendance of employees etc.


<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 16-April-2022**

## Fetching data from another doctype in doctype
Today I was trying to fetch the fields in the souvenir doctype from other doctypes and  sehjal and pawandeep also helped me in this we were able to fetch branch name (username) etc. After that i was trying to migrate the souvenir doctype. I am not able to do it on my local erpnext as i am getting an error related to supervisor. I was trying to create an app named souvenir so that one can easily fork it from my repository but i was getting error so vishal created an app named souvenir on his local erpnext and added it to his github and i tried to fork it from his repository again i am getting error related to souvenir.



<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 18-April-2022**

## Error On local erpnext 
Today I was continuously getting error ;) related to supervisor vishal and I was trying to resolve this issue but after applying solutions for this error we were getting new errors so we uninstalled the local bench then reinstalled it on our local system. After this I created a
new app named Souvenir_Form then installed it on site. Then I have created a new doctype named Souvenir and a web form named souvenir on my local system.


<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 19-April-2022**

## Presentation Of all the topics
Today I gave presentation to all my mates in which i had covered all the topic that i have learnt during training like budibase, docker, erpnext and all the basic topics of education domain like student applicant, programs, courses, instructor, workflow, notifications,
souvenir etc. Currently I am working on web form validation I have found some solutions that how to add events for validations and where to add
validation. I will try to add these in my files and test these events.



<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 20-April-2022**

## Validations on web form
I and pawan implemented the validations in the souvenir web form like
in phone number field user can only enter 10 digits,  and crn and urn
field will accept only 7 digit numbers. I have added the whole project
as an app on the github and anyone can install it on their site and
the link is  https://github.com/kanchan1427/Sovenier2022.git   Now i
am trying to fetch the details of users form the user list (prefilled
form) and image specifications.



<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-April-2022**
## Installation of Souvenir app on Gne11
I have installed the souvenir_form app on gne11.gndec.ac.in. I was getting server exceptions on the web form. After some time it was working well and i was able to enter the data in the form. 


<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-April-2022**
 
## Validations on web form
Today I and pawan did the validations on web form as previously we had implemented validations on web form but wasn't proper validations. As it was just showing the error message after cancelling the error the user information was getting saved. So it was not proper validations. So we again implemented the validations with proper functions and events and tested it properly as a tester. 


<!----------------------------------------------------------------------------------------------------------------------------->
 **Date : 23-April-2022**

##Working to fetch data from user doctype in souvenir doctype
Today I and Pawan was trying to fetch the data from user doctype to souvenir doctype. We were searching for the solutions for fetching the fields from another doctype. By default in the erpnect their is "fetch from" option is available in doctypes but we wanted to do it from backend so we implemeted it by using java script events that are present in official documentation of erpnext. We implemented it in js file of souvenir doctype. By using these events we were able to fetch the data like name,email,contact number from user doctype.


<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-April-2022**

## Fetching Data on web form
Today we were trying to get the prefilled data in the souvenir web form so that user doesn't need to fill the information agaian and again as all the information is previously available. We implemented the same function which we had applied in doctype but these events are not working on the web form. To find the another alternative event we are searching online and watching youtube tutorials but till now we haven't got any
 solution ;) . We are trying our best to get it done as soon as possible.

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-April-2022**

## Presentation on Souvenir Project 
Today I gave presentation to all my mates on souvenir project. I
showed them all the requirements and specification. I also showed them
the overall workflow of the project and what i have done till now and
what is the required output.

Today i was trying to implement value =
frappe.web_form.get_value([fieldname]); ,
frappe.web_form.set_value([fieldname], [value]) these functions are
working in the doctype i am trying same functions in the web form but
these are not working in the doctype maybe I am not writing it in
correct format. I will try to implement these functions in correct
format.



<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 27-April-2022**

## Successfully fetched data from souvenir doctype to souvenir web form
Today we succesfully fetched the data from souvenir doctype to the souvenir webform :) . But our main task was to get it form user list ;) .
 we successfully  did populate the souvenir doctype from user doctype and
then i was trying to fetch the data  to the webform but it didn't work
but when we add data to the souvenir_doctype
it will auto populate the webform.
I found this discussion and here one say fetch doesnt work on webform.
so we are now figuring out different menthod 

<!----------------------------------------------------------------------------------------------------------------------------->
 **Date : 28-April-2022**

## Presentation of souvenir
 Today i gave presentation to all my mates and juniors. We have explained all the requirements of souvenir to the juniors and after that sir explained us all the flow of the project and there were some requirements that we have missed. 
 
<!----------------------------------------------------------------------------------------------------------------------------->
  **Date : 29-April-2022**

## Testing of Souvenir
 Today we have tested the souvenir project as a tester. There were some errors in the projects. If a user is updating his previous filled information than it creating a new entry for the same user rather than updating his details in the previous information.
<!----------------------------------------------------------------------------------------------------------------------------->
  **Date : 30-April-2022**

## Hierarchy of Nankana Sahib Education Trust
 
 Today we have discussed the hierarchy and structure of Nanakana sahib
education trust, gndec, nsps.

Basic Structure:- First we have a parent company Nankana sahib
education trust and under these we have child companies Guru nanak dev
engineering college, Nankana sahib public school (21 branches), Guru
nanak dev polytechnic college, ITI.

Accounts Structure:- First we have a parent company NSET and it has a
bank account which will take care of all the accounts of child
companies. Under the parent company we have a child company gndec
which also has a fee account and a salary account all the tuition fee
of students will directly go to the fee bank account , and all the
amount of fee bank account will be transferred to the salary account
and all the employees will get their salaries from the salary account.
All the development fee will be directly transferred to the
development account. For the development company will get the
amount/fund from  the development account.

Roles  in NSET:- In the nankana sahib education trust we have
president , director, managerial staff and under the president we have
sub roles for other users, secretary, and trustees. and under the
managerial staff we have clerks and accountant. Only the received
amounts and all benefits should be visible to the instructor. Only the
accounts part should be visible to the director.Clerk is responsible
for all the inventories stocks. Clerk2 will be responsible for the
hostlers fee.And they should be able to see only their assigned
company details.

NSET:-
In NSET company we have a director role which should have access to
all the child companies. All the child companies GNDEC, NSPS have a
principal.After that other staff is divided into two sections one is
Non-teaching and other is teaching.Under the non-teaching staff we
have clerks, accountants, assistants and other staff. Teaching section
is further divided into Examination, student section(admissions etc),
Establishment, Department. The examination staff will take care of
examinations of companies, the student section will take care of the
students admissions,fees etc.In the departments we have the role of
HOD, section incharge, staff.
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 2-May-2022**

## Hackathon day 1
 Roles and flow for Parent Comapany:-

Director:- Director will have all permissions like fees, salary, accounts , total gain etc but with read only access.

Accountant:- will have permissions to see all the account information of trust, nsps, gndec. Accountant will have read, write access to create the fee and salaries of the employee and also can create the fee report and salary report.

HR:- HR will have permission to create the users and make them employees, leave allocation, holiday list, salary of employee. Superintendent
Roles and flow for Child Comapany:-

Principal:- Will have only read only access to all the education domain related information and HR related information.

Accountants:- 1 For students fee and 1 for salaries of employees. Teaching Incharge:- Will do all the tasks of academic user like course scheduling etc.

HR:- will create employees and instructors only for Nankana sahib Public School, leave allocation, salary of employees etc. We need to show all the reports like employees attendance report, salary report, leave report etc to the HR..

Instructors:- will have access to student attendance, quiz, videos, article, Diary, Student list etc.
 <!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 03-May-2022**

## Hackathon day 2
 
 Students:- will have access of only LMS and on lms they will have access of programs, Courses, Quizzes, Videos, Articles, daily diary and attendance.

Accountant:- will create the salaries of employees and fees of students, will generate the balance sheet.

We need to generate all the reports and graphs for necessary information for each role.

Inventory Management

Today, We created Director user of NSET, Superintendent of NSET, Principal user of NSPS and HR user of NSPS on erp server and gave them all the required permissions. And same roles are created on gne11.GNE, whose credentials are shared in other mail. You can check that roles with given credentials. Also we learn about Salary Structure and Salary Component of employees. In meeting with Harpreet sir, we learn about PF, Taxes, Funds, Earnings and Deductions etc. We will explore it and implement on gne11.GNE.
 <!----------------------------------------------------------------------------------------------------------------------------->
  **Date : 4-May-2022**

## Assessment and report cards
 
 I have explored the assessment section of education domain.
For the assessment we need to create Assessment Criteria, Assessment
Group , Assessment Plan , Grading scale.

Assessment criteria:- Assessment Criteria is the parameter based on
which you assess the Student. For example Theory and practical.

Assessment Group:- Assessment Group tree is a master where you can
define the hierarchy for examination conducted in your education
institute.
For example:- 2022-23 ->sem 1-> mst 1, mst2 , finals and sem 2-> mst1,
mst 2, finals.

Assessment Plan:- An Assessment Plan is a schedule to conduct the
examination/assessment of a particular course for a group of students
studying that course in an on-going academic term.
It contains all the information like schedule time, room number,
program, course, date, supervisor, examiner etc.

Grading Scale:- In Grading Scale, you can define the threshold for
the different grades obtained by the students, based on their scores
in the assessment.For example, Students obtaining a score of 90% and
above would be graded as A+, students obtaining a score of 80% and
above would be graded A- and so on.

Assessment Result:- In this we can generate the report card of
students. We need to add the marks manually for each assessment
criteria to generate the report card.

I have added a quiz and an article in course so that students can
attempt it on lms. These quizzes and articles are not related to the
report cards. After attempting the quiz students will get their marks
immediately. 
 <!----------------------------------------------------------------------------------------------------------------------------->
**Date : 5-May-2022**

## Creating Presentation in Revel.js 
 
 Created Presentation for the Whole Project To so that we can present our work to the trusties so with the team we created a presentation which contains all the infomation related to the erp Syatem which deals with the all kind of accounting, maintaing all students,staff and employees and pushed on github.

 <!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 6-May-2022**

## Finding the Solution For the error
 
 There were some error in the souvenir project as it was creating new entries for users after they update their informtaion in the previous information rather than updating it in the previous information. So I was trying to find the solution for the error i have tried some js function in the .js file but error was still there so i am finding another solution for the error.
 <!----------------------------------------------------------------------------------------------------------------------------->
 
  **Date : 7-May-2022**

## Finding the Solution For the error
 
 There were some error in the souvenir project as it was creating new entries for users after they update their informtaion in the previous information rather than updating it in the previous information. So I was trying to find the solution for the error i have tried some js function in the .js file but error was still there so i am finding another solution for the error.
 <!----------------------------------------------------------------------------------------------------------------------------->

**Date : 9-May-2022**

## Image Specifications To Web From
 
 First I tried to get the image path file from the user that uploads it and then from the use of that source Got the Image Width and Height and then put some conditions and make it validate. First got some errors like it saves the form even after errors shown. the need to put some frappe web form components.In the end It works like charm. sample code is as follows:

  
                var img = new Image();
                 img.src = value;
                 img.onload = function () {
                     var height = this.height;
                     var width = this.width;
                     console.log(height, width)
                     frappe.web_form.validate = () => {
                     if ((height > 1000 || width > 1000) || (height < 350 || width < 350)) {
                         frappe.throw("Height and Width must be Between 1000px and 350px");
                         return false;
                     }
                     return true; 
                 }
     
                 }


 
 <!-----------------------------------------------------------------------------------------------------------------------------> 
  **Date : 10-May-2022**

## Creating the view of souvenir
 
 First we were implementing the view of souvenir in which we were just fetching the details of souvenir doctype in the view but yesterday sir
told us to create a webpage for instructor. Today we(I and pawan) had a meeting with sehjal as had implemented mentor mentee before so we
were trying to understand the concept of that app and the coding. They hadn't implemented the mentor mentee in erpnext she implemented it in
frappe. So she created her own doctypes and added a mentor field in the student doctype by using which she was able to fetch mentees of
mentor. But in the  erpnext we already have student doctype and instructor doctype even we have a student group in which we can assign
a mentor to a instructor. Now we are trying to create logic for mentor mentee by using all these doctypes.

 <!----------------------------------------------------------------------------------------------------------------------------->
**Date : 10-May-2022**

## Creating the view of souvenir
 
 I am implementing the view of souvenir in which we were just fetching the details of souvenir doctype in the view but yesterday sir
told us to create a webpage for instructor. Today we(I and pawan) had a meeting with sehjal as had implemented mentor mentee before so we
were trying to understand the concept of that app and the coding. They hadn't implemented the mentor mentee in erpnext she implemented it in
frappe. So she created her own doctypes and added a mentor field in the student doctype by using which she was able to fetch mentees of
mentor. But in the  erpnext we already have student doctype and instructor doctype even we have a student group in which we can assign
a mentor to a instructor. Now we are trying to create logic for mentor mentee by using all these doctypes.

 <!----------------------------------------------------------------------------------------------------------------------------->

**Date : 11-May-2022**

## New requirements of Souvenir
 
 Today We have got new requirements of souvenir projects.
 There will be  a web page for instructors.

He will get a list for all his mentees.

On clicking a mentee, he will get all comments, and may be an "edit box"
for his comment. He may click the best comment, and that must be
copied to his edit box, where he further edit and polish it and save,
and repeat the same for next mentee.
 
 Now we are trying to understand the flow of these requirements and will implement it.
 <!----------------------------------------------------------------------------------------------------------------------------->
**Date : 12-May-2022**

## Creating Webpage for the instructor
 
We were trying to create a webpage for instructors. After giving a web view to the souvenir doctype we were trying to fetch the details of
the student group doctype in the souvenir web view. But we are not able to fetch the student group details because its domain is
different. Now we are searching for a way to do this.

 <!----------------------------------------------------------------------------------------------------------------------------->

**Date : 12-May-2022**

## Creating Webpage for the instructor
 
 Today We were trying to create a web page for instructor with a condition if the instructor has access to A class then on web page the
instructor will have only the class A's students.But we are unable to map the mentor with his mentees. We want to show the instructor only his assigned class students. After clicking on the students he will get all the comments of the each student.

 <!----------------------------------------------------------------------------------------------------------------------------->


**Date : 13-May-2022**

## updatingthe image specifications of souvenir
 
 First I tried to get the image path file from the user that uploads it and then from the use of that source Got the Image Width and Height and then put some conditions and make it validate. First got some errors like it saves the form even after errors shown. the need to put some frappe web form components. We updated  the rules of image specifications.
 
 <!----------------------------------------------------------------------------------------------------------------------------->

**Date : 14-May-2022**

## Exploring CRM module in erpnext
 
 Today I am working on CRM module in erpnext.CRM helps you track business Opportunities from Leads and Customers, send them Quotations, and book Sales Orders.CRM has various terms like Lead, sales, reports, setup, marketing, article.
I will explore all these terms.
 
 In CRM under the sales section we have

Lead:- A lead is a potential customer who might be interested in your
products or services. For example if we are advertising some products
and people are interested in our products and they come to check out
our products. These are our Leads.

After creating a lead erpnext is providing us many features like auto
assignment by using which we can assign a lead to a particular user.
Adding Multiple Contacts and Addresses:- In order to close a sales
deal, you will have to contact multiple people working in the
prospective company. You can add the details of all such people in the
same lead.
Recording Comments, Emails :- We can have comments under a lead , and
also we can send email/ reply to the customer from the lead.


 <!----------------------------------------------------------------------------------------------------------------------------->

**Date : 16-May-2022**

## CRM in erpnext
 
opportunity:- When you get a hint that lead is looking for a
product/service that you offer, you can convert that lead into an
opportunity.

features of opportunity:-
Auto-close Opportunities:- If you do not receive a response from an
opportunity for a certain number of days, you may want that
opportunity to be closed automatically. We can set no. of days in the
sales settings. Lead will close automatically close if there isn't any
response within the set no. of days.

Auto assignment:- We can assign the opportunity to a particular user.

Capture the Reasons and Competitors for Lost Opportunities:- When an
opportunity is lost, you can capture the reasons, competitors and
detail reason for losing. This will help you to analyse the trends
over a long period of time and identify the insights needed for
improvements at various areas in the organisation.

 <!----------------------------------------------------------------------------------------------------------------------------->
**Date : 17-May-2022**

## Sales section under CRm in erpnext
 
 
In the CRM under the Sales section we have

Customer:- Customer is the one who receives goods, services, products,
or ideas, from a seller for monetary consideration. Customer will have
a unique id we can set customer name as a unique id or we can give
them a naming series as a unique id.

Features:-
Multiple Contacts and Addresses:- We can add multiple addresses and
contact details for a single customer

Default Currency and Price List:- We can can set the default currency
to be used for this customer in sales orders and sales invoices by
selecting the appropriate currency in Billing Currency.

Credit Limit and Payment Terms:- We can set the credit limit by
entering the amount in 'Credit Limit' field

Or we can see the complete accounting ledger for a particular user.

 <!----------------------------------------------------------------------------------------------------------------------------->


**Date : 18-May-2022**

## HR and Buying module in erpnext
 
 Today Sir has assigned us a new task. I and Aman will explore the HR and Buying module in the erpnxt. We have shared all the templates for required data with some temporary data.
 
The Human Resources (HR) module covers the processes related to the HR department of a company. It maintains a complete employee database including contact information, salary details, attendance, performance evaluation, leaves, and appraisal records.
The most important feature here is processing the payroll by using Payroll Entry to generate Salary Slips. Most countries have complex tax rules stating which expenses the company can make on behalf of its Employees.
There are a set of rules for the company to deduct taxes and social security from employee payroll. ERPNext accommodates all types of taxes and their calculation.
 <!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 19-May-2022**

## HR and Buying module in erpnext

 In the HR domain we have Shift Management module.The Shift Management
module in ERPNext HR helps us efficiently manage shifts for our
employees.
Under the shift Management we have Shift type, Shift assignment, shift request .

Shift type:- In the shift type doctype we can create multiple shifts
of our company like morning, evening etc. It contains Name of the
shift, start time and end time of shift.

Shift Request :- Shift request  is used by employees of a company to
request for a particular shift.

Shift Assignment:- when the employee requests for a particular shift
and when the shift request is approved and submitted then the system
will automatically  assign shifts to the employees
 <!----------------------------------------------------------------------------------------------------------------------------->
**Date : 21-May-2022**

## HR module in erpnext
 
 In the HR module We ca add employee, can mark their attendence, generate their salraies,Fleet management, performance appraisal etc. Employees can also request for leave. 
 <!----------------------------------------------------------------------------------------------------------------------------->

**Date : 23-May-2022**

## Buying module in erpnext
 
 Today I and aman was exploring the buying module. In Buying, we need to have items, suppliers and warehouses.
In this, firstly we will create a Material Request for the items that we want to buy, then a request for quotation will be created against that material request. Email will be sent to the suppliers and they will submit the supplier quotation. Then it will be visible to us in
the supplier quotation list. We will choose the best quotation among all of them. After that, we can create a purchase order.

 <!----------------------------------------------------------------------------------------------------------------------------->

**Date : 24-May-2022**

## View According to roles in the desk
 
Today Sir has assigned me a new task. I am work on what should be visible to a particular role in the desk view. I will also compare the
current system (Fee bank) of Nankana Sahib Public School with the erpnext.Today I am reading the files of erpnext and also exploring
desk so that we can change the view / sidebar based on the roles.
 

 <!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-May-2022**

## View According to roles in the desk
 
We were finding a way to generate/ update the view according to the role. We haven't found anything in the files of erpnext and on desk. Sowe have checked all the posts on the communutity related to this for the solution. In the community they are saying currently it is not possible to
restrict the modules according to the roles. But we can do this for each user.Means if there is an instructor role  and we want to restrict
the other modules for instructor role except the education module.This is not possible to do this for role. If there are 10 instructor
users then we can do this for each user.
<!----------------------------------------------------------------------------------------------------------------------------->
 
**Date : 26-May-2022**

## Solution for the view according to role
 
In the community they are saying currently role basedpermissions are not available. SO we were trying to find another way for this like script or csv file etc.
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 27-May-2022**

## csv file for the view
 
 Today we have created the csv file for every instructor so that we can block all the other modules in the instructor view except education module. We have also implemented it for a single instructor for testing purpose. Only the ducation domain is visible to the instructor.
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-May-2022**

## Desk Theme
 
 -Sir assigned us (Me and Jaspreet) the task to beautify the desk view with bootstrap. So we are exploring about it.
 - We found theme of desk. We install a theme from this url: https://github.com/hashirluv/r
 -After installing this theme, colour of heading, navigation bar etc got changed.
 - Then we tried some other themes also. We tried White Theme, Blue Theme etc.
 - Then we understand the code and css files to change the view of desk. We can change only background colours, text colours, hover text colour etc with    some changes in the css files.
 <!----------------------------------------------------------------------------------------------------------------------------->
**Date : 30-May-2022**

## Compare Student Record with new data
 
 Today, I compare students record with the new data provided by NSPS. I have to add new students in the system etc.
<!----------------------------------------------------------------------------------------------------------------------------->
 
**Date : 31-May-2022**

## Active and Deactive Students
 
 - We can check all active students and deactive students in the system.
 - Deactive students are those who have not paid their fees after a particular date.
 - We can check all active/deactive students from student list.
 - Go to student list. Add a filter with “Enabled” equals “Yes” in the student list. Count of all active students will show there.
 - To check Deactive students, change value of Enable to No. Then all deactive students will be visible.
 - We can also check Gender wise Active or Deactive students by applying Gender equals Female or Male filter.

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-June-2022**

## Class and Section wise Active/Deactive Students
 
 - There is no Program field in the student doctype.
 - So we have to customize the doctype and add a new field Program and link it to the Program DocType.
 - After this, we can check count of active or deactive students class-wise and section-wise.
 - For class-wise, add a filter of program for example Program like Class 8.
 - For section-wise, add a filter of program. For example Program equals Class 8 A.
 
<!----------------------------------------------------------------------------------------------------------------------------->

