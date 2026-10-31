pipeline {
    agent none
 
    stages {
        stage ('Windows Stage') {
            agent {
                label 'windows'
            }
           steps {
               bat 'echo Hello from Windows'
               bat 'whoami'

           }
           }
            stage ('Linux Stage') {
            agent {
                label 'linux'
            }
           steps {
               sh 'echo Hello from Linux'
               sh 'whoami'
           }
            }
           stage ('Docker Stage') {
               agent {
            docker {
                image 'alpine:3.20'
            }
               }
           steps {
               sh 'echo Hello from Linux'
               sh 'whoami'
            
           } 
                    
                }
                    
                }
                    
                }
