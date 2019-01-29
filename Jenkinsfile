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
                sh "dokcer build -f Dockerfile"
            }
        }
    }
}
