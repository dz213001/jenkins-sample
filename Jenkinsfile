pipeline {
    agent none 
      parameters {
        string(defaultValue: "TEST", description: 'What environment?', name: 'userFlag')
          // choices are newline separated
          choice(choices: 'US-EAST-1\nUS-WEST-2', description: 'What AWS region?', name: 'region')
      }


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
