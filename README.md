
# reuse Spring MVC and Hibernate template application

This is a template for a web application that uses Spring MVC and Hibernate. The sample code is a simple CRUD page that manipulates records for a single model object.

## Running the application locally

First build with:

    $mvn clean install

Then run it with:

    $java -jar target/dependency/webapp-runner.jar target/*.war


# AppStore0507

This project provides an introduction to full-stack web app development using JAVA. 

In this project, we are going build a web application similar to the Google Play or Apple appstore with the goal of providing users with an easy to navigate page where they can browse available apps. The app store will use the following technologies: JAVA using Spring-MVC[1] framework, Hibernate ORM[2], MySQL[3] (data storage), Tomcat 8.0[4] (web server), and AngularJS[5] (UX).

The major functionalities are : 
app information will be provided in a raw dataset and then loaded into a MySQL database;
the final interface will filter the home page to only show the top 10 apps;
finally, if the user wishes to learn more about an app, they will be able to click on an app and be directed to a details page.

