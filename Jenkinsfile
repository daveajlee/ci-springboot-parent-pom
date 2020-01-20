node {
   def mvnHome = tool 'Maven 3.5.3'
   stage('Git Checkout') {
      // Get code from contact-microservice GitHub repository
      git 'https://github.com/daveajlee/ci-springboot-parent-pom.git'
   }
   stage('Build') {
      // Run the maven build
      sh "'${mvnHome}/bin/mvn' clean install"
   }
}
