pipeline {
  agent any
  stages {
    stage('Get input') {
      steps {
        input(message: 'Give Centos name', id: 'centosName')
      }
    }

    stage('show input') {
      steps {
        sh 'echo $centosName'
      }
    }

  }
}