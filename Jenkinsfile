pipeline {
    agent any
stages {
        stage("clone code") {
            steps {
                script {
                    // Let's clone the source
                    git 'https://github.com/lilfrou/angular.git';
                }
            }
        }
    stage('cleaning stage') {
             steps {
              sh "mvn clean" 
              sh "mvn clean install" 
                 sh "mvn -v"
                 
        }
    }  
         
 }  
   
}
