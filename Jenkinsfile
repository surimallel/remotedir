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
        stage ('Functional Test') {
           steps {
               echo "This is Functional Test"
           }
            }
        stage ('Regression Test') {
           steps {
               echo "This is Regression Test"
           }
            }
        stage ('Smoke Test') {
           steps {
               echo "This is Smoke Test"
           }
            }
            }
        }
                    
                }
}
