pipeline {
   agent any 
  tools { 
     gradle "gradle-4.0"
        maven 'Maven 3.3.9' 
        jdk 'jdk8' 
    }
   
   stages {
      stage('TreeVeiw-build') { 
        steps {
            sh "/build.gradle"    
        }
      }
   }
}
