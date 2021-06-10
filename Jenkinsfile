pipeline {
  agent {
    node {
      label 'principal'
    }

  }
  stages {
    stage('Stage 1 - Build') {
      steps {
        echo 'Fase 1 de Stage Build'
      }
    }

    stage('Stage 2 - Test') {
      parallel {
        stage('Stage 2 - Test') {
          steps {
            echo 'Running Unit Test....'
            echo 'Running Integration Test....'
            echo 'Running Aceptacion Test....'
          }
        }

        stage('') {
          steps {
            echo 'Testing!!'
          }
        }

      }
    }

    stage('Stage 3 - Deploy') {
      steps {
        echo 'Deploying artifact!!!'
      }
    }

  }
}