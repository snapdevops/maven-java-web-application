pipeline {
    agent any

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
