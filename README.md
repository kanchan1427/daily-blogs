
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
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Introduction to Selenium, Budibase</h3>
- Selenium is browser automation tool by which you can create a script which automatically done task like fill credential and click for search.
- Budibase is a development platform designed for speed and productivity. 
- <p align="justify">With Budibase, developers no-longer experience repetition, long-dev cycles, and frustration. Instead, developers are more productive, happier, and can deliver applications they're proud of in minutes.</p>
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


<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 17-Feb-2022**
<h3 align='center'>Create CRUD app using MySQL in budibase</h3>

For creating CRUD app click on "https://docs.budibase.com/docs/build-a-crud-app".<br>


<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 18-Feb-2022**

<h3 align='center'>Creating LMS </h3>
<p align="justify"></p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 19-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 21-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 22-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->



<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 23-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> </h3>
Today sir has assigned the task to explore education domain.I am reading the documentation and trying to understand it.
<p align="justify"> </p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 24-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->


<h3 align='center'> learning about the modules of education domain</h3>
<p align="justify"> I am learning about the modules of education domain.
Under faculty modules I have added teachers and checked the database entries .Today I have also learnt about GitHub basic commands like commit ,push.
</p>
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 25-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'> basic setup of education domain</h3>

<p align="justify"> </p>
 Today I have done the basic setup of education.First I created Programs, Course, Academic year, Academic Term etc.


<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 26-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>basic setup of education Student Module </h3>

<p align="justify"> I am uderstanding the concept of Student module in erpnext.I created Student, Student group etc.
</p>
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 28-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>  </h3>
Today I am trying to understand how i can assign courses, programs, enroll
students in programs and how to alot instructors to the students
according to a school and done it on my local.
<p align="justify"> </p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 01-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Sceduling Module</h3>
<p align="justify"> Today I implementing the course Schedule on my local</p>

<!----------------------------------------------------------------------------------------------------------------------------->


**Date : 01-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'> Support Module</h3>
<p align="justify">I am exploring Managing issue web form.
Issue can be created in two ways. One is through the web portal after logged in and issue is created in the backend. Another one is through emails on support address and issue is created in the backend.
</p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 11-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Assesement Module</h3>
<p align="justify">Today I implemented the assessment module in
gne11.gndec.ac.in.
First I have created  Assessment Creteria . For example, if the assessment was conducted for english or other subject, then we canevaluate Student in English on various criteria like Writing, internal assessment(viva), Attendence etc.Assessment criteria can be used while scheduling assessment plan for
student group and course.
Then next , I have created Assessment group tree (hierarchy for examination conducted in school) for one batch i.e 2021-2022 . As shown in following screenshot.
**Assessment plan**

Next I created Assessment plan which is schedule to conduct the examination/assessment of a particular course for a group of students in an on-going academic term. For creating Assessment plan the prerequisites is grading scale so, we need to create grading scale for it.

Grading Scale

Grading scale define the threshold for the different grades obtained by the students, based on their scores in the assessment. For example , I have created grading scale of Students obtaining a score of 100%  would be graded as O, students obtaining a score of 80% and below would be graded A- and so on.
After creating Assessment plan for course 'English-4/A/MST -1'. Then
there is Assessment Result.

Assessment Result

Assessment Result is log of marks/grades earned by the student for
specific Assessment. Basically we can use Assessment Result Tool for
creating log of marks of multiple students at the same time . It is
based on Assessment plan.

 </p>

<!----------------------------------------------------------------------------------------------------------------------------->


**Date : 12-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Setup of Assessment Module </h3>
<p align="justify">Today I have done the setup of Assessment module.</p>

<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 14-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Result creation of students</h3>
<p align="justify"> Today I am testing the assesment module, where the result of all the students in coursewise.For that first i have to create assessment plan for each course.Then get the reult of that particular assessment plan.</p>
<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 15-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Report Generation of student</h3>
<p align="justify"> In the erpnext education module I was trying to generate report card for students while creating report card I am able to show the courses and exams but not able to show the marks of students in the report card.I have assigned the marks to the particular students.</p>

<!----------------------------------------------------------------------------------------------------------------------------->
