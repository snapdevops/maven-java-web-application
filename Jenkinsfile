pipeline {
    agent 
    stages {
        stage('Build') {
            agent any
            steps {
                checkout scm
                sh "mvn clean install"
                // build
             }
        }

        }
  }


