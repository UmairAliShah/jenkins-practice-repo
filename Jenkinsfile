pipeline{
   agent any
   tools {
        maven 'Apache Maven 3.6.0'
   }
   stages {
      stage('Preparation') { 
         steps{
           git 'https://github.com/talhakhannnnn/jenkins-practice-repo.git'
         }
       }
      stage ('Compile Stage'){
         steps{
               bat "mvn clean compile"
         }
      }
   }
}
