pipeline {
    agent {
        docker { image 'siemenslabbinck/getting-started' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
