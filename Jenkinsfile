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
           sh "cd frontend/src/main/web && ng build"
                 

                 
        }
    }  
         
 }  
   
}
