pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Howdy World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
