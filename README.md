# ci-parent-pom
This is a Maven Parent POM for Continuous Integration using the latest version of Spring Boot with Java 8. It includes the standard Spring Boot Starter as Parent POM as well as the Spring Boot Test Starter POM as dependency. In addition, an analysis profile can be called which runs Surefire for JUnit Tests, measures Code Coverage using Cobertura, generates Documentation using JavaDoc and measures Code Quality using PMD, FindBugs and Checkstyle.

This POM can be used as a Parent POM for any Maven Project wishing to use Spring Boot, Java 8 and Continuous Integration. To use the POM as a Parent POM add the following code to your POM (you will need to have placed this POM in a repository management system such as Sonatype Nexus):

```
<parent>
	<groupId>de.davelee</groupId>
	<artifactId>ci-parent-pom</artifactId>
	<version>0.1.0-BETA-SNAPSHOT</version>
</parent>
```
