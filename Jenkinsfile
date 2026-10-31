pipeline {
    agent {
        label 'windows'
        
    }
 
    stages {
        stage ('check agent'){
            steps {
                script {
                    ehco "Name" : ${env.NODE_NAME}
                    ehco "Workspace" : ${env.WORKSPACE}
                }
            }
        }

        
        stage ('windows command') {
           steps {
               bat 'echo Hello from Windows'
               bat 'whoami'
            
           }
                
                    
                }}}
