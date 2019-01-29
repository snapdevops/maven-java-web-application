pipeline {
    agent {
        def commitHash = checkout(scm).GIT_COMMIT
    }
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


