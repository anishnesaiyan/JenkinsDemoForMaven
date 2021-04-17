pipeline {
  agent any
  stages {
    stage('Development') {
      steps {
        echo 'Pull the code from git hub'
        echo 'Create build'
      }
    }

    stage('QA') {
      steps {
        echo 'QA deploy'
        git(url: 'https://github.com/anishnesaiyan/JenkinsDemoForMaven', branch: 'master')
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}