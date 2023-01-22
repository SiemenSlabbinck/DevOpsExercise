pipeline {
    agent {
        docker { image 'siemenslabbinck/getting-started' }
    }
    triggers {
        pollSCM '*/5 * * * *'
    }
    stages {
        stage('Build') {
            steps {
                echo 'building..'
                sh 'node --version'
            }
        }
        stage('Test'){
            steps {
                echo 'Testing..'
                sh '''
                echo "doing test stuff"
                '''
            }
        }
        stage('Deliver'){
            steps{
                echo 'Deliver..'
                sh '''
                echo "doing deliver stuff"
                '''
            }
        }
    }
}
