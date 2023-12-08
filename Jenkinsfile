ipipeline {   
    agent any

    stages {   
        stage('sprint branch') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint') { 
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
