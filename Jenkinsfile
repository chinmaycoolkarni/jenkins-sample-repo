pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/chinmaycoolkarni/jenkins-sample-repo.git'
            }
        }

        stage('Install dependencies') {
            steps {
            }
        }

        stage('Execute Python script') {
            steps {
                sh 'python hello-world.py'
            }
        }
    }
}
