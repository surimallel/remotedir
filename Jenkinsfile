pipeline {
  agent any

  stages {
    stage ('Build') {
      steps {
        echo 'building an application'
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
