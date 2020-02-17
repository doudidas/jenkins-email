pipeline {
  agent any
  stages {
    stage('Get input') {
      steps {
        script {
          def CENTOS_NAME = input message: 'Give Centos Name', ok: 'Next'
        }

      }
    }

    stage('show input') {
      steps {
        script {
          echo "Selected machine: ${CENTOS_NAME}"
        }

      }
    }

  }
}