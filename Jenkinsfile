pipeline {
    agent none 
    // properties([parameters([choice(choices: ['UAT', 'PROD'], description: 'Choose env', name: 'Env')])])
     parameters ([
       string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?'),
       booleanParam(name: 'DEBUG_BUILD', defaultValue: true, description: '')
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
