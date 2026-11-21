pipeline {
    agent any

    stages {
        stage('Checkout Git') {
            steps {
                git branch: 'main',
                url: 'https://github.com/Sinda-sakouhi/sakouhi-sinda.git'
            }
        }

        stage('Build Maven') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
