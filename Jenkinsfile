pipeline {
    agent {
        label 'windows'
        
    }
 
    stages {
        stage ('check agent'){
            steps {
                script {
                    echo "Name" : ${env.NODE_NAME}
                    echo "Workspace" : ${env.WORKSPACE}
                }
            }
        }

        
        stage ('windows command') {
           steps {
               bat 'echo Hello from Windows'
               bat 'whoami'
            
           }
                
                    
                }}}
