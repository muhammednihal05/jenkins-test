pipeline {
  agents any
  stages {
    stage('Build') {
      steps {
        echo 'Build Stage Passed'
      }
    }
    stage('Test') {
      steps {
        echo ' Test Stage Passed'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy Stage passed'
        sh '$(date)'
      }
    }
  }
}
