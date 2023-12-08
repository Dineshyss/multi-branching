pipeline {   
    agent any

    stages {   
        stage('hotfixes branch') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('hotfixes') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
