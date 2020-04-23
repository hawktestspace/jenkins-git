pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
        stage('DDH Test') {
            steps {
                sh 'echo "Executing \"DDH Test\" stage from Jenkinsfile"'
            }
        }
    }
}
