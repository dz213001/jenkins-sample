pipeline {
    agent none 
    parameters {
        choice(choices: 'DEV\nUAT\nPROD', description: 'ENV', name: 'env')
    }
    
    triggers {
      cron('@daily')
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
