@Library('Santu_SharedLibraries') _



pipeline {
    agent any
    stages {
       stage('Testing') {
        steps {
             welcomeJob("Santu!")
          
          
        }
       }
      stage ("mvn test") {
        steps {
          jenkinsForJava('https://github.com/abcdsantu/santu-appnew.git')
        }
      }
      
    }
 }
