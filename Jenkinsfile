pipeline {
  agent any
  stages {
    stage('Get input') {
      steps {
        script {
          def vm = input(id: 'userInput',message: 'give VM Names',
          parameters: [
            string(defaultValue: 'None', description: 'centos', name: 'centos')
          ])
          def centos = vm.centos
        }

      }
    }

    stage('show input') {
      steps {
        sh 'echo Selected machine: ${centos}'
      }
    }

  }
}
