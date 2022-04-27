
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-Feb-2022** 
<h3 align='center'>Introduction to Linux & Installing Ubuntu</h3>

<p align="justify">Linux is an open-source operating system like other operating systems such as Microsoft Windows, Apple Mac OS, iOS, Google android, etc. An operating system is a software that enables the communication between computer hardware and software. It conveys input to get processed by the processor and brings output to the hardware to display it. This is the basic function of an operating system.</p>

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
<h3 align='center'>Introduction to LAMP Stack</h3>

<p align="justify">The LAMP stack is a popular open-source solution stack used primarily in web development.LAMP consists of four components necessary to establish a fully functional web development environment. The first letters of the components' names make up the LAMP acronym:</p>

- Linux is an operating system used to run the rest of the components.
- Apache HTTP Server is a web server software used to serve static web pages.
- MySQL is a relational database management system used for creating and managing web databases, but also for data warehousing, application logging, e-commerce, etc.
- PHP, Perl, and Python are programming languages are used to create web applications.
- Installing lamp on Ubuntu System.
- Verifying by run LAMP on localhost.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 3-Feb-2022**
<h3 align='center'>Introduction to frappe</h3>

<p align="justify">Frappe, pronounced fra-pay, is a full stack, batteries-included, web framework written in Python and Javascript with MariaDB as the database. It is the framework which powers ERPNext, is pretty generic and can be used to build database driven apps.</p>
**Why Frappe?
<p align="justify">The key difference in Frappe compared to other frameworks is that meta-data is also treated as data. This enables you to build front-ends very easily. We believe in a monolithic architecture, so Frappe comes with almost everything you need to build a modern web application. It has a full featured Admin UI called the Desk that handles forms, navigation, lists, menus, permissions, file attachment and much more out of the box.</p>

- Install Frappe-bench and its required tool. For more info [Click here](https://frappeframework.com/docs/v13/user/en/installation).
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 4-Feb-2022**
<h3 align='center'>Creating App and Site & run on local server in Frappe</h3>

- Start Bench in one Terminal.
- In Second Terminal.
- Creating App by using **bench new-app library_management** inside Frappe-bench Directory.
- Creating site by using **bench new-site library.test** inside Frappe-bench Directory.
- Run Site on Localhost by using library.test custom port name.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 5-Feb-2022**
<h3 align='center'>Introduction to Github Pages</h3>

- Getting Information What is GitHub Pages.
- Create a New Repository on GitHub.
- Setting Repository as the main branch and setting a theme for GitHub pages.
"policy domain="path" rights="none" pattern="@*"- Learning about Personal access tokens for push Local Repository on GitHub.
- Learning Syntax of Markdown Language in GitHub.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date:7-Feb-2022**
<h3 align='center'>Introduction to budibase</h3>

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
<h3 align='center'>Introduction to Github Pages</h3>

 Today one of my mate gave us a presentation on github.
 He explained us what is github pages and how to create a repository.
 -How to set a repository as the main branch and setting a theme for github pages.
 -How to send push and pull request in github.
"policy domain="path" rights="none" pattern="@*"- Learning about Personal access tokens for push Local Repository on GitHub.
- Learning Syntax of Markdown Language in GitHub.
<br>
 
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 9-Feb-2022** 
<h3 align='center'>Introduction to Reveal.JS, Pandoc, Use of Markdown in Reveal.js</h3>

- What is Reveal.JS, Pandoc, Use Markdown in Reveal.js.
- Creating Presentation in Reveal.JS using Markdown only.
- Learn how to show presentation on Local machine.
- Converting .md file into .pdf file using Pandoc.
<br>

<!---------------------------------------------------------------------------------------------------------------------------->

**Date : 10-Feb-2022** 
<h3 align='center'>Introduction to Docker, Virtual Machine </h3>

**What is Docker?**
<p align="justify">Docker is popular virtualization software that helps its users in developing, deploying, monitoring, and running applications in a Docker Container with all their dependencies (frameworks, libraries, etc.) to run an application in an efficient and bug-free manner.Docker Containers are Light-weight, Applications run in isolation,Occupies less space, Easily portable and highly secure, Short boot-up
time.</p>
- It can run multiple containers on a system.
- It can start multiple containers at a time on the Docker engine.
<br>

**What is Virtual Machine?**
<p align="justify">A Virtual Machine (VM) is a compute resource that uses software instead of a physical computer to run programs and deploy apps. One or more virtual “guest” machines run on a physical “host” machine.  Each virtual machine runs its own operating system and functions separately from the other VMs, even when they are all running on the same host. This means that, for example, a virtual MacOS virtual machine can run on a physical PC.</p>
- It can start only a single VM on a VMX.
- It can run only a limited number of VMs on a system.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 11-Feb-2022** 
<h3 align='center'>Create a CRUD app in budibase</h3>

<p align="justify">Building apps with Budibase involves 4 simple steps:

Install Budibase - Use Budibase Cloud to get started in seconds, or self-host your apps using Docker, Kubernetes , or DigitalOcean.
Add data - You can connect to data sources like PostgreSQL, Rest APIs, MS SQL, MySQL and more, or start from scratch with Budibase's built-in database (Budibase DB, built on top of CouchDB).
Design your UI - Build beautiful, accessible user interfaces people enjoy using. Autogenerate CRUD screens from your data, or create custom screens from scratch. Use powerful components, such as tables, buttons, form inputs, to enrich your interface. Switch from light mode to dark mode with just a click.
Automate processes - In seconds, setup automations such as email alerts, Slack notifications, CRON actions, and more.</p>

For creating CRUD app click on "https://docs.budibase.com/docs/build-a-crud-app".
 Today i am done with the installation of erpnext.
 There was a presentation by one of my mates on frappe and how to create library mangement system in frappe framework.The presentation was good.they told us about the installation steps of frappe bench and how to create LMS and pros and cons of frappe like if we have to add users or articles then its is not possible to upload in bulk we need to upload them manually one by one.and how to create app,site and how to add articles and doctypes in LMS.
 <br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 12-Feb-2022**
 <h3 align='center'>Introduction to Selenium, Budibase</h3>
- Selenium is browser automation tool by which you can create a script which automatically done task like fill credential and click for search.
- Budibase is a development platform designed for speed and productivity. 
- <p align="justify">With Budibase, developers no-longer experience repetition, long-dev cycles, and frustration. Instead, developers are more productive, happier, and can deliver applications they're proud of in minutes.
 today there was a presentation on salenium by kiran she showed us how to implement salenium she implemented it on guru portal where she automated the login on guru portal without manual click.</p>
- 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 14-Feb-2022**
<h3 align='center'>Understanding the concept of budibase app </h3>
I am currently working on budibase. Today i was reading the concept of apps that how they are created in Budibase.
I haven’t done anything extra on budibase except reading the documentation and understanding the concept of built- in apps in budibase

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 15-Feb-2022**
<h3 align='center'>Working on Job portal app in budibase</h3>
if you want to access a budibase app without login, you will need to make some "Public" screens, and browse directly to the URL for those screens.

You will also need to make sure that your public screens are only accessing tables/queries that have "Public" access. Beware that this will mean that all data in those tables will be public (if "Read" is set to Public).
And I successfully make all screens public.
I checked how all pages are created in job portal app. How it to be published.
I am currently working on budibase. Today i was reading documents related to docker so that i can find any alternatives of dockers and to find is it possible to publish app in budibase without using docker.
 
 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 17-Feb-2022**
<h3 align='center'>Working on Budibase</h3>

 Today I am working on budibase and trying to create an app i am able create all the tables and enteries in it but when i am trying to create view of pages i am getting error. I am not able to map their views.

 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 17-Feb-2022**
<h3 align='center'>Create CRUD app using MySQL in budibase</h3>
 
 Today I was trying to create crud app-MySQL but there is an error related to database . And I am reading the documentation of erpnext (education domain) and  learnt how to create students and instructors.
For creating CRUD app click on "https://docs.budibase.com/docs/build-a-crud-app".<br>


<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 18-Feb-2022**

<h3 align='center'>Working on ERPNEXT </h3>
<p align="justify">Today i started working on new platform erpnext it is open source, and low code or no platform. It is fun to work on a wonderful platform they provided us so much funtionality with number of modules like education domain, crm, website etc and all these are available inside a single platform and if we want to do modifications it is also possible in the erpnext :) 
 Today i am reading the documentation of erpnext to understand the education domain. Today i have created some programs and courses now i am trying to understand how to enroll students in programs and courses.
</p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 19-Feb-2022**
 <h3 align='center'>Installation of MOSH and TMUX</h3>
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
 
 <h3 align='center'>Working on ERPNEXT </h3>
<p align="justify">I am working on education domain of erpnext in this i have created programs and courses. In erpnext program means classes and courses means subjects. And i also did the enrollments of students in the programs and courses. Now i am trying to understand the studnets groups in erpnext.
</p>
 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 22-Feb-2022**
 
<h3 align='center'>Working on ERPNEXT </h3>
<p align="justify">Today i am working on student group which are avialble in erpnext these are like a student sections. We can create students based on courses, Acedemic term, Activity which will help us to do group actions like if we want to generate fee of a student group at a time then it will help us in that instead of generating the fee of  single single student.
</p>
 

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 23-Feb-2022**
 
 <h3 align='center'> </h3>
Today sir has assigned the task to explore the strcuture of erpnext. I am reading the documentation and watching youtube videoes and trying to understand it:)
 Today I have learnt what is erpnext, architecture of erpnext, what is
the role of frappe in erpnext, how erpnext is different from
traditional softwares, what is doctype and field types. 
<p align="justify"> </p>


<!----------------------------------------------------------------------------------------------------------------------------->


<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 24-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->


<h3 align='center'> Understanding the structure of erpnext</h3>
<p align="justify"> Today I have learnt what is erpnext, architecture of erpnext, what is the role of frappe in erpnext, how erpnext is different from
traditional softwares, what is doctype and field types. It is very interesting as i am having fun while doing this.
</p>
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 25-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Understanding the structure of erpnext</h3>
 Today i have learnt how we can add and delete instructor, students, courses from backend. and i am trying to understand the structure of
erpnext. It is very simple as all the doctypes in erpnext have a table with same name in the database and we can delete, insert and update enteries of all the doctypes by using basic mysql queries.
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 26-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Understanding the structure of erpnext</h3>

<p align="justify"> Today i am working on erpnext structure. I am trying to understand how views, modals and controllers are generated in erpnext and how to customize them. I am reading the official documentation and watching youtube videos to understand this. It is very difficult to understand the complete structure of erpnext as it is very big platform :(  but i am doing my best to understand it.
</p>
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 28-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Basic setup of erpext on server</h3>
Today Sir has assigned me a task to do basic setup of erpnext on server. Sir gave me admin access so that i can do it on server and told me to check how one can apply for a particular program.
 For this First i created programs some with frontend and some by using import tool, Then i created courses with import tool, and successfully imported some students and instructors in the erp and assigned them programs and courses. And i am trying to understand what is cost center in erpnext.
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 01-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Installation of chat app on erpnext version 13</h3>
<p align="justify"> I and vishal installed the chat app on erpnext version 13 and it is working fine. It wasn't avialable with the official erpnext v13.
 We did:-
$ bench get-app chat
$ bench --site your-site install-app chat
</p>

<!----------------------------------------------------------------------------------------------------------------------------->


**Date : 02-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'> Reading the documentation of erpnext</h3>
<p align="justify">Today I was reading the documentation of erpnext and trying to understand the instructor section of education domain. I got to know that while creating the instrcutor first we need to create the employee and assign them a particular company and after assigning the company we can make the same employee an instructor. Then we can assign them a particular program and courses. 

</p>

<!----------------------------------------------------------------------------------------------------------------------------->
 
 **Date : 03-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'> Instructor Module</h3>
<p align="justify">Today I was exploring the instructor and website module in erpnext . I
implemented it in erpnext on my local device. Trying to explore all the duties and roles of instructor that are present in erpnext and also i am trying to understand the website module.

</p>

<!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 04-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Meeting app</h3>
<p align="justify">Today vishal and pawan gave us a presentation of meeting app. They showed us how to create custom apps in erp and how to install it onto the site. And they also showed us the code of the app and structure and files of the meeting app. 
 Working on instructure section of education module of erpnext. 
</p>

<!----------------------------------------------------------------------------------------------------------------------------->
 
  **Date : 05-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Notice Board app</h3>
<p align="justify">Today we all created a notice board app in erpnext within 30 minutes. It was a wonderful experience as we can created such apps withiin a short time period.
</p>

<!----------------------------------------------------------------------------------------------------------------------------->


  **Date : 07-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Basic setup for Nanakana Sahib Public School</h3>
<p align="justify">
Today I am done with the basic setup of Nankana Sahib Public
School. I have created three programs Class 1, Class 2, Class 3 and
three instructors for each class , four courses for each class, and
2-2 topics per courses, three room and other basic requirements.
I have imported data of 8 students using the data import feature in
erpnext and also tried to update the existing record which is working
fine without any issue.

</p>

<!----------------------------------------------------------------------------------------------------------------------------->
  **Date : 08-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Notification After Applying for a program</h3>
<p align="justify">Today sir assigned me a task to import all the students and applicants. And if a student is applyig for any programs then after filling the web form he should get a notification for id and password creation after the submission of web form.
</p>

<!----------------------------------------------------------------------------------------------------------------------------->
 
 **Date : 09-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Notification After Applying for a program</h3>
<p align="justify">I was searching that how a student can get a notification after fubmission of the web form. For this i was reading the official documentation and watching youtube videos. After Investing so much time i got to know that in the erpnext there is inbuilt notification feature and we can apply condition in notifications for when and for what we want to send notifications.</p>

<!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 11-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Notification After Applying for a program</h3>
<p align="justify">I was searching that how a student can get a notification after fubmission of the web form. For this i was reading the official documentation and watching youtube videos. After Investing so much time i got to know that in the erpnext there is inbuilt notification feature and we can apply condition in notifications for when and for what we want to send notifications.</p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 12-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Notifications and student registration via form</h3>
<p align="justify">Now when i am trying to add student applicant via form i am getting
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

 </p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 14-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Workflow and Basic Setup Nankana Sahib Public School</h3>
<p align="justify">Today I created a workflow for the student applicants which has some state like approved by admission manager, approved by instructor, Approved by hod. First admission checker will acept or reject the application of students if it is accepted then instructor will get a notification for the this. Next instructor will approve or reject it if it is accepted the hod will accept it or reject it. 
 
Today we all have done the basic setup again for Nankana Sahib Public School for Class 1 to Class 8 and imported students, instructors and enrolled them in programs, courses and assigned instructors to the programs. As it was very difficult for all of us to understand because there were many same enteries of two companies one of Nankana Sahib Public School and another of Guru Nanak Dev Engineering College and there were many enteries that we all have entered for testing purpose. So today we all deleted all the previous enteries to do the setup from scratch. It was very helpful for all of us as there  were some doubts of us related to program enrollment , course enrollment  and student group.
</p>
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Course Scheduling</h3>
<p align="justify"> Today we all have implemented course scheduling via course scheduling tool , assessment plan, attendance by using attendance tool, we were also exploring the student leave application but the problem is if we have added an application for leave and also approved it but after approving if an instructor is trying to add attendance of whole class via attendence tool then it marking everyone present including students with leave application. Today we all have explored learning management system in erpnext too "https://gne11.gndec.ac.in/lms"  which is basically student interface.
I was also working on emails basically "how we can disable email must be unique" in erpnext and I have found a solution for this problem for this we have to open the doctype and to click on customize doctype and then go to email field type then click on edit in full page there is an checkbox named "Unique"  then just uncheck it.
Now I was exploring how do I can add parents in erpnext and what are the requirements and I have found that there is an option named
guardians in erpnext education module now I am working on it.
</p>

<!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 16-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Report Card Generation</h3>
<p align="justify">In the erpnext education module I was trying to generate report card
for students while creating report card I am able to show the courses
and exams but not able to show the marks of students in the report
card,
</p>

<!----------------------------------------------------------------------------------------------------------------------------->
  **Date : 17-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Guardian Module</h3>
<p align="justify">I was exploring guardians modules in erpnext . I have created a
guardian in education module there are two ways to create a guardian
one by creating a user first then assign that user id to the guardian
and other is we can directly create a user in the guardian doctype
then there is a button named  "invite as user" after this in both the
methods a invitation mail is sent to the user to complete their
registration or to set a password. I was following
"https://docs.erpnext.com/docs/v13/user/manual/en/education/guardian"

But in this they haven't mentioned which type of role and permissions
we need to assign to a parent user.</p>

<!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 19-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Gunicorn, Socket.io, Scaffhold </h3>
<p align="justify">Today we got to know three new terms that are used in frappe first is 
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
</p>

<!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 21-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Reading the excellent reports by seniors</h3>
<p align="justify">Today i was reading the three report that was written by our seniors.
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
</p>

<!----------------------------------------------------------------------------------------------------------------------------->
 **Date : 22-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Installing new Erpnext on server</h3>
<p align="justify">First we install frappe framework then install erpnext with education domain.
 - After this we are collecting students and teachers data from Nankana Sahib Public School. - Arranging data according to doctype in erpnext. 
</p>

<!----------------------------------------------------------------------------------------------------------------------------->
 **Date : 23-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Comparing "http://103.66.206.229:8001/gne" in mobile and laptop</h3>
<p align="justify">Today Sir told me to comapre this site in mobile view as well as in laptop view. As there was some problem in the mobile view. Also I was working on the ducation domain of erpnext and trying to understand it. 
</p>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 24-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Working on Leave management</h3>
<p align="justify">Today i was trying to understand the default workflow of employee leave management system means how employee can add their leaves and how HR/Department head will get the leave notification and how they will accept the leaves. And I was exploring the types of leaves and the salary cut for the leaves.</p>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 25-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>HElping others in their tasks</h3>
<p align="justify">Today i Was helping others in their tasks. I </p>
helped Jaspreet in importing instructors as there were some issue we both were trying to resolve it and after investing some time in it it got resolved.
 After this I helped Sehjal in importing And adding the students in erpnext. And was trying to understand their tasks.
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 26-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Naming series According to the company</h3>
<p align="justify">Today Sir assigned me and vishal  a task to change the naming series of student applicant doctype according to the company abberivation so that we can identify the students of each company(school/college) by looking at their naming series. There was a solution avialable in the official documentation of erpnext and we tried it but it wasn't working. We also tried some changes but still it wasn't working. After this we  were searching for the other solutions and there was a solution available in the discussion forum. We tried it on local machines and it was working perfectly after this we implemented it on gne11.gndec.ac.in</p>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 28-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Trying to understand the student leave section</h3>
<p align="justify">Today I am trying to understand the student leave section under education domain of erpnext. I was trying to understand the default workflow of student leave section. how students will add their leaves and how instructor will get notification of the leaves.  </p>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 29-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Created new web-form and doctype for trainees</h3>
<p align="justify">Today i created a doctype named trainees_details with some fields and after that i created a web form based on this doctype. after creating this i gave web view to the doctype and after this i added it on the website so that students can fill their personal information.</p>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 30-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Integration of Erpnext with moodle</h3>
<p align="justify">Today sir gave me a task to find a solution to integrate erpnext with moodle.After searching i got to know a new tool by which we can integrate erpnext with moodle.Myddleware for Moodle enables you to transfer your data easily and
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

</p>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 31-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Enabling chat options for the student users/h3>
<p align="justify">First we install frappe framework then install erpnext with education domain.
 - After this we are collecting students and teachers data from Nankana Sahib Public School. - Arranging data according to doctype in erpnext. 
</p>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 22-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Installing new Erpnext on server</h3>
<p align="justify">First we install frappe framework then install erpnext with education domain.
 - After this we are collecting students and teachers data from Nankana Sahib Public School. - Arranging data according to doctype in erpnext. 
</p>

<!----------------------------------------------------------------------------------------------------------------------------->

