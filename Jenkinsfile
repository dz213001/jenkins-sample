pipeline {
    agent none 
    stages {
      properties([parameters([choice(choices: ['UAT', 'PROD'], description: 'Choose env', name: 'Env')])])
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
