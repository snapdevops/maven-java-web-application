pipeline {
    agent any
      try {
    stage('Checkout') {
      checkout scm
    }

    stages {
        stage('Devlopment Build') {
            steps {
                echo 'Building..'
                sh "mvn clean install"
            }
        }
        stage('Deploy') {
            steps {
                sh "docker --version"
                //sh "docker build -f Dockerfile -t"
            }
        }
    }
}
