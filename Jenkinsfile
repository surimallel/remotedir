pipeline {
    agent {
        docker {
           image 'alpine:3.20' 
        }
        
    }
 
    stages {
        stage ('showinput') {
            steps {
                script {
                    def branchName = env.BRANCH_NAME
                    echo "Branch name ${branchName}"
                    
                    if (branchName == 'master') {
                        echo "Production"
                    }
                    else if (branchName == 'develop') {
                        echo "RUN UAT"
                    }else {
                        echo "Validation"
                    }
                    
                }
                
                    
                }}}}
