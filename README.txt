About
-----

HelloWebApp is a Java Web Application that serves as a bare-bones starting point for new web application projects. Read more at the website:

  http://xeiam.com/

Features
-----

* a working Ant build file that compiles, packages and deploys a .war file to a local web container
* Servlet 3.0 annotations
* Servlet to JSP attribute passing

Installation
------------

Should build right out the box. Edit the 'tomcat.dir' parameter in build.properties to reflect the correct location of your web container on your 
local machine. Run the 'deploy_local' Ant task. View the web application with the following URL (assuming that you're running the web container 
on port 8080): http://localhost:8080/HelloWebApp/

Tested with Tomcat 7. 