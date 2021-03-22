
 <h2> Maven Projects and Wizard Tool</h2>

• Maven is a build automation tool used primarily for Java projects. Maven
can also be used to build and manage projects written in C#, Ruby, Scala,
and other languages.<br>
• Eclipse Maven Tooling manages the project dependencies and updates
the classpath of the project dependencies in the Eclipse IDE. It ensures
that the Maven experience in Eclipse is as smooth as possible. The
tooling also provides different kind of wizards import and to create new
Maven based projects.<br>
• It also provides an editor for the pom.xml Maven configuration file via a
structured interface. You can select the tab labeled pom.xml to edit the
XML data directly.<br>

<b>Ability to show Hello World Message when running Java Maven Application in Eclipse IDE</b>
(Create HelloWorld Maven Project)

<b>step 1</b> go to File -> new -> project -> Maven -> select "Maven project" click "Next" Buttion -> click Next bution<br>
<b>step 2</b> type Filter:- "quickstart" and select "org.apache.maven.archetypes" and click "Next" buttion<br>
<b>step 3</b> i m going to Group ID for the Artifact <br>
		Group ID:-com
		Artifact ID:-javaPractice
		and click "Finish"

<b>Ability to show Hello World Message using Log4j2 Logging Library when running Java Maven Application in Eclipse IDE</b>

<b>Step1-</b> I m going to “src/main”<br>
<b>Step2-</b> select main and Right click and Go to “New” Go to “Folder” -> Folder Name  write Here- “Resource” and click “Finish” Button.<br>
<b>Step3-</b> Then select “Resource” Folder Then click right click Go to “New” then Go to “File” write here File Name- “log4j2.xml” and click “Finish” Button.<br>
<b>Step4-</b> I m going to chrome and search “maven repository log4j2” -> ” Apache Log4j Core” select latest version “2.14.1”  and copy maven Dependency code:-
<!-- https://mvnrepository.com/artifact/org.apache.logging.log4j/log4j-core -->
<dependency>
    	<groupId>org.apache.logging.log4j</groupId>
    	<artifactId>log4j-core</artifactId>
    	<version>2.14.1</version>
</dependency>
Go to the “pom.xml” and Past it  Dependency code.<br>
<b>Step5-</b> I m going to chrome and search “maven repository log4j2” -> ” Apache Log4j API” select latest version “2.14.1”  and copy maven Dependency code:-
<!-- https://mvnrepository.com/artifact/org.apache.logging.log4j/log4j-api -->
<dependency>
    <groupId>org.apache.logging.log4j</groupId>
    <artifactId>log4j-api</artifactId>
    <version>2.14.1</version>
</dependency>
Go to the “pom.xml” and Past it  Dependency code
