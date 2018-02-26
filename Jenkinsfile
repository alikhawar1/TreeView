pipeline {
   agent any 
  tools { 
     gradle "gradle-4.0"
        maven 'maven 3.3.9' 
        jdk 'jdk 9.0.4' 
    }
   
   stages {
      stage('TreeVeiw-build') { 
        steps {
              sh 'chmod +x build.gradle'
            sh "./build.gradle classes"    
        }
      }
   }
}
