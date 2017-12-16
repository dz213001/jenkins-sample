pipeline {
  agent none 
    options([parameters([choice(choices: ['UAT', 'PROD'], description: 'Choose env', name: 'Env')])])
    stages {
      stage('Example Build') {
        steps {
          echo 'Hello, Maven'
        }
      }
      stage('Example Test') {
        steps {
          echo 'Hello, JDK'
        }
      }
    }
}
