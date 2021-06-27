pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'git@github.com:gjagadish473/pipeline.git', branch: 'main')
      }
    }

    stage('build') {
      steps {
        sh 'ls -ltr'
      }
    }

    stage('upload') {
      steps {
        sh 'ls'
      }
    }

    stage('deploy') {
      steps {
        sh 'ls'
      }
    }

  }
}