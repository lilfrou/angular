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
           sh "cd frontend/src/main/web && npm install"
           sh "cd frontend/src/main/web && npm run build"
           sh "cd frontend/src/main/web && npm publish"
                 

                  
        }
    }  
         
 }  
   
}
