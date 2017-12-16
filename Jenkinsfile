pipeline {
    agent none 
    // properties([parameters([choice(choices: ['UAT', 'PROD'], description: 'Choose env', name: 'Env')])])
    parameters([booleanParam(defaultValue: false, description: '', name: ''), string(defaultValue: '', description: '', name: '')])


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
