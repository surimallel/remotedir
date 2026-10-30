pipeline {
    agent any
 
    stages {
        stage ('showinput') {
            steps {
                script {
                    def branchName = env.BRANCH_NAME ?: 'manual'
                    echo "Branch detected: ${branchName}"
                    
                    if (branchName == 'main') {
                        echo "Production"
                    }
                    else if (branchName == 'develop') {
                        echo "RUN UAT"
                    }else {
                        echo "Validation"
                    }
                    
                }
                
                    
                }}}}
