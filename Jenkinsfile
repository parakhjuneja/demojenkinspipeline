pipeline {
  agent any
  stages {
    stage('testing') {
      steps {
        sh '''pwd
ls
echo "hi we are initiating testing now"
cal 2023'''
      }
    }

    stage('testing-deploy') {
      steps {
        echo 'we are initiating test deploy'
        sh 'sleep 10'
      }
    }

  }
}