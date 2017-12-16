pipeline {
    agent none 
    // properties([parameters([choice(choices: ['UAT', 'PROD'], description: 'Choose env', name: 'Env')])])
      properties([
          parameters([
            booleanParam(
              defaultValue: false,
              description: 'isFoo should be false',
              name: 'isFoo'
              ),
            booleanParam(
              defaultValue: true,
              description: 'isBar should be true',
              name: 'isBar'
              ),
          ])
      ])


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
