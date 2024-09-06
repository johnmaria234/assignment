# assignment- login test 
steps to execute file
1. copy the .java file from the repository
2. open eclipse on your computer
   Prerequisite: Java should be installed
  ( java can be downloaded from :https://www.oracle.com/in/java/technologies/downloads/
   eclipse could be downloaded from :https://www.eclipse.org/downloads/packages/release/kepler/sr1/eclipse-ide-java- 
   developers)
4. click File>new>Java project
5. enter the Project name>click Finish
6.  Right click on the project created (shown in package explorer)
7.  create new>Package  (locate the package from src folder in project)
8.  Right click on the package create new>class
9.  copy the code from the Logintest.java file and paste in the new class created
10.  add the selenium jar files to classpath/build path
11.  run the class


login test case of website -https://app.germanyiscalling.com/common/login
# testcases 
 ## testcase1 ( valid login )
login with valid email and password should redirect to userprofile
Result was as expected
 ## testcase2 ( invalid login )
 login with invalid email and invalid password should show error message-"Please enter a correct username and password"
 Result was as expected
 ## testcase3 ( empty login )
 login with empty email and password should show error message-"Email: This field is required. Password: This field is 
 required."
 Result was as expected
 Enhancement: Error message could be more precise like-"email and password field can't be empty"
