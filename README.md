# ci-springboot-parent-pom
This is a Maven Parent POM for Continuous Integration using Java with Spring Boot. It includes the standard Spring Boot Starter as Parent POM as well as the Spring Boot Test Starter POM as dependency. In addition, an analysis profile can be called which runs Surefire for JUnit Tests, measures Code Coverage using Cobertura, generates Documentation using JavaDoc and measures Code Quality using PMD, FindBugs and Checkstyle.

## Version 1.1.0 with Java 8 & Spring Boot 1.5.0
This POM can be used as a Parent POM for any Maven Project wishing to use Spring Boot, Java 8 and Continuous Integration. To use the POM, you must download it manually (see assets on the right-hand side of the screen) and install it into your Maven repository. Then you can use the POM as a Parent POM by adding the following code to your POM:

```
<parent>
	<groupId>de.davelee</groupId>
	<artifactId>ci-springboot-parent-pom</artifactId>
	<version>1.1.0</version>
</parent>
```
