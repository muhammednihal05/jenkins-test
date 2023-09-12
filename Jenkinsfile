def gv

pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        script {
          gv= load 'scripts.groovy'
        }
      }
    }
    stage('Build') {
      steps {
        script {
          gv.buildApp()
        }
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
        sh 'date'
      }
    }
  }
}
