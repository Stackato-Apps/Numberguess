Number guess application
------------------------

This simple sample aims to demonstrate the support of JEE6 applications (JSF, Annotation, Injection etc.).

Building the Application
------------------------

It is possible to build the application either with Ant or Maven.

### Ant

Make sure your have [Ant](http://ant.apache.org/ "Ant") installed.
Then, *cd* into the root directory and execute:

	ant clean package
	
That will create the *numguess.war* file within the 'target' directory.

### Maven

Make sure you have [Maven](http://maven.apache.org/ "Maven") installed.
Then, *cd* into the root directory and execute:

	mvn clean package

That will create the *numguess.war* file within the 'target' directory.

Running the Application
-----------------------

To run the application, make sure you have the HPE Helion Stackato client installed and that you are logged in successfully for your desired target environment.

Then execute:

	stackato push -n

Then go on your application url.

That's all. Have fun!
