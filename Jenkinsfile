pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    echo "Roman2"
                    ls -lah
                '''
            }
        }
    }
}
