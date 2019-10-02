# helloWorld

Java "hello world" program
This repository contains very trivial web program consisting of JSP page . To build and run this program, follow the instruction:

$ mvn clean
$ mvn package
$ cp hello.war $TOMCAT_HOME/webapps
$ service tomcat restart
 

Note that you should have to install JDK 8, Maven and Tomcat 7 as prerequisite.
