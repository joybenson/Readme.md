 # Using Maven to build Project



 Maven is a build automation tool used for java projects. It's also used to execute [jar,war,ear] packages.
 
 It can be used also to build and manage other languages[RUBY and SCALA]. Maven provides a standard path to describe dependencies, build processess and project structure.


 ## Installation of MAVEN on windows


 Visit the official Apache Maven website at '''https://maven.apache.org/download.cgi''' and download the latest version of Maven. Choose the binary zip archive option.
  
  Extract the Maven archive.

  Set up Environmental variables and Save. Environmental variables can be found in 'THIS PC/MY COMPUTER'.

  To verify installation, open a command prompt[cmd] and type 'mvn -version'. It will show the information about the maven version installed.



  ### Creating Maven project on windows

  Open the Command Prompt on the windows system and create a diectory, then navigate into this directory the project would be created.
  
  '''bash

  mkdir project001

  '''
  #

  '''bash

  cd project001

  '''
  #

  '''arduino

  mvn archetype:generate -DgroupId=REWE.war -DartifactId=REWE-001 -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

  '''
  #

  '''bash
  cd REWE-001

  '''
