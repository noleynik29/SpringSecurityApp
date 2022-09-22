# SpringSecurityApp

Java Spring Security App using: spring web mvc, javax servlet, spring security web, spring security config, spring security taglibs, mysql connector java and c3p0.

To run this project better use the newest version of IntelliJ IDEA, JDK 1.8_x, Tomcat 9.0.x and newest version of MySQL Workbench.

Also you need to download and run this sql code ([settings.txt](https://github.com/noleynik29/SpringSecurityApp/files/9625243/settings.txt)) to create database, that will be used in app. 

If you've got any problems caused by this upgration, better look up the documents in Spring Framework Reference.

Firstly, when you start this application with Tomcat, you will see this authentication page:

![enter](https://user-images.githubusercontent.com/71104368/191736587-285dd0ae-ac19-42d3-bcfb-73298203c3ec.png)

Application has multiple views depending on user role. You can login as Employee, HR or Manager.

To login as Employee use login and password "zaur". You will see this simplest web-page with info for every Employee, HR and Manager:

![emp](https://user-images.githubusercontent.com/71104368/191737483-b122e2e7-ccaa-49b2-9149-dba1548f3070.png)

To login as HR use login and password "elena". You will see this simplest web-page with info for HRs and Managers:

![hr1](https://user-images.githubusercontent.com/71104368/191737890-ce929f1a-200c-4220-bb93-58320161812c.png)

And you have a "Salary" button to open new page with everyones salaries (it's empty):

![hr2](https://user-images.githubusercontent.com/71104368/191738047-35dbc44c-f77c-4621-805e-ee4448f7d2ff.png)

And the last, you can login as Manager. To do this use login and password "ivan". You will see this simplest web-page with info only for Managers:

![man1](https://user-images.githubusercontent.com/71104368/191738426-83d6f8db-0e13-40d8-94b7-088fa03f8a37.png)

Managers can see the same view that HRs see, and even more to have all information about Employees, HRs and other Managers.

![man2](https://user-images.githubusercontent.com/71104368/191738695-2fe1d657-3f77-41e2-b7a3-2a2592c7f48b.png)

Usernames and password are stored in database that you have created in the beginning. Passwords are crypted by bcrypt. Bye
