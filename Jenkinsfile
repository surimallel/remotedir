pipeline {
  agent any

  stages {
    stage ('Build') {
      steps {
        echo 'building an application'
        sh 'exit 1'
      }
    }
  }
  post {
    always {
      echo "pipeline finished"
    }
    success {
      echo "pipeline success"
    }
    failure {
      echo "pipeline failed"
    }
  }
}
