pipeline {
  agent any
  stages {
    stage('Get input') {
      steps {
        script {
        // Show the select input modal
          def CENTOS_NAME = input message: 'Give Centos Name', ok: 'Next',
        }
      }
    }

    stage('show input') {
      steps {
        echo "Selected machine: ${CENTOS_NAME}"
        
      }
    }

  }
}
