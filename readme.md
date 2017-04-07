Walking skeleton of an executable JAR application using Maven as build system. Concept based on ideas from book "*Growing Object Oriented Software Guided by Tests*" by Steve Freeman and Nat Pryce.

#"*...we write test infrastructure to drive our non-existent application, so that we can make the first test fail.*"

Simplest version includes just a basic POM template and single (failing) end-to-end acceptance test fixture based on RobotFramework.

To fail the test:

	gradlew build runrobot