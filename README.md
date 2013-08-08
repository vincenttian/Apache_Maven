mvntest
=======
This helped me become familiar with Maven. 

It is awesome that Maven downloads the libraries that I use and and the libraries that my libraries use automatically.

It's simple to add dependencies to my pom.xml file, especially with the Maven repository: http://mvnrepository.com/

These are the steps to creating this project: See http://maven.apache.org/guides/getting-started/maven-in-five-minutes.html for additional info

Step 1.  Create a directory and start a shell in that directory

Step 2. 
Command: mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

After cd-ing into the directory which is the same name as the artifactId, all files are automatically generated.

This is the standard project structure for a Maven project.
