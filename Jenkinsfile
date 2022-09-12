pipeline {
  agent any
  stages {
    stage('pull from Git') {
      steps {
        git(url: 'https://github.com/izzeddincelik/jenkinsTest.git', branch: 'master')
      }
    }

    stage('Build') {
      steps {
        echo 'Hello World'
        sleep 10
      }
    }

  }
}