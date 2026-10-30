pipeline {
    agent any
 
    stages {
        stage ('showinput') {
            steps {
                script {
                    def branchName = sh (
                        script: 'git branch --show-current',
                        returnStdout: true
                    ).trim ()
                    echo "Brnach name detected: ${branchName}"
                    
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
