pipeline {
    agent any
 
    stages {
        stage ('Build') {
           steps {
               echo "This is the build stage.."

           }
           }
        stage ('Tests') {
            parallel {
            stage ('Unit Test') {
           steps {
               sh 'sleep 3'
               echo "This is Unit Test"
           }
            }
           stage ('App test') {
           steps {
               echo "This is App Test"
            
           } 
                    
                }
        stage ('UI Test') {
           steps {
               echo "This is UI Test"
           }
            }
            }
        }
                    
                }
                    
                }
