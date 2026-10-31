pipeline {
    agent {
        label 'windows'
        
    }
 
    stages {
        stage ('windows command') {
           steps {
               bat '''
               echo Hello from Windows
               whoami
               hostname
               ver
            '''
           }
                
                    
                }}}
