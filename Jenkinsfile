pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            echo 'testing testing'
          }
        }

        stage('Parallel') {
          steps {
            echo 'meow testing running'
          }
        }

      }
    }

    stage('build') {
      steps {
        echo 'building'
      }
    }

    stage('Clean up') {
      steps {
        echo 'Cleaning'
      }
    }

  }
}