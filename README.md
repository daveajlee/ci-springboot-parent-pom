# ci-springboot-parent-pom

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/e0665e016519416b96b6741a52bb89ec)](https://app.codacy.com/manual/dave_33/ci-springboot-parent-pom?utm_source=github.com&utm_medium=referral&utm_content=daveajlee/ci-springboot-parent-pom&utm_campaign=Badge_Grade_Dashboard)

This is a Maven Parent POM for Continuous Integration using Java with Spring Boot. It includes the standard Spring Boot Starter as Parent POM as well as the Spring Boot Test Starter POM as dependency. In addition, an analysis profile can be called which runs Surefire for JUnit Tests, measures Code Coverage using JaCoCo (version 2.x and higher) or Cobertura (version 1.1.x), generates Documentation using JavaDoc and measures Code Quality using PMD, FindBugs (version 1.1.x only) and Checkstyle.

## Version 3.0.0 with Java 17 & Spring Boot 3.0.5
This POM can be used as a Parent POM for any Maven Project wishing to use Spring Boot 3, Java 17 and Continuous Integration. You can use the POM as a Parent POM by adding the following code to your POM (assuming you have GitHub packages as a repository already defined):

```
<parent>
	<groupId>de.davelee</groupId>
	<artifactId>ci-springboot-parent-pom</artifactId>
	<version>3.1.0</version>
</parent>
```

## Version 2.3.0 with Java 14 & Spring Boot 2.3.3
This POM can be used as a Parent POM for any Maven Project wishing to use Spring Boot 2, Java 14 and Continuous Integration. To use the POM, you must download it manually (see assets on the right-hand side of the screen) and install it into your Maven repository. Then you can use the POM as a Parent POM by adding the following code to your POM:

```
<parent>
	<groupId>de.davelee</groupId>
	<artifactId>ci-springboot-parent-pom</artifactId>
	<version>2.3.0</version>
</parent>
```

## Version 2.2.0 with Java 13 & Spring Boot 2.2.3
This POM can be used as a Parent POM for any Maven Project wishing to use Spring Boot 2, Java 13 and Continuous Integration. To use the POM, you must download it manually (see assets on the right-hand side of the screen) and install it into your Maven repository. Then you can use the POM as a Parent POM by adding the following code to your POM:

```
<parent>
	<groupId>de.davelee</groupId>
	<artifactId>ci-springboot-parent-pom</artifactId>
	<version>2.2.0</version>
</parent>
```

## Version 1.1.0 with Java 8 & Spring Boot 1.5.0
This POM can be used as a Parent POM for any Maven Project wishing to use Spring Boot, Java 8 and Continuous Integration. To use the POM, you must download it manually (see assets on the right-hand side of the screen) and install it into your Maven repository. Then you can use the POM as a Parent POM by adding the following code to your POM:

```
<parent>
	<groupId>de.davelee</groupId>
	<artifactId>ci-springboot-parent-pom</artifactId>
	<version>1.1.0</version>
</parent>
```
