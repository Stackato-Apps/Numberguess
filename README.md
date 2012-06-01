Number guess application
------------------------

This simple sample aims to demonstrate the support of JEE6 applications (JSF, Annotation, Injection etc.).

Building the Application
------------------------

To build the application, make sure you have [Maven](http://maven.apache.org/ "Maven") installed.
Then, *cd* into the root directory and execute:

	mvn clean package

That will create the *numguess.war* file within the 'target' directory.

Running the Application
-----------------------

To run the application, make sure you have the Stackato client installed and that you are logged in successfully for your desired target environment (e.g. http://api.stackato.local).

Then execute:

	mvn clean package
	stackato push -n 

Notice that it detected the app type as "Java Web Application". In this case, it's only recognizing a runtime (Java)
but not a framework (e.g. Spring or Grails), since this really is just a barebones Java web application. If you were
to create a Spring or Grails application, you would see that it detects both the runtime and the framework.
