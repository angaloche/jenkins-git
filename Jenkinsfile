pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World hmida"'
                sh '''
                    echo "YO Yo Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
