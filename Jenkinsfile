pipeline {
    agent { 
        label 'agent1'
    }
    stages {
        stage('build') {
            steps {
                sh 'docker build -t express:app .'
            }
        }
    }
}
