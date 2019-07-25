pipeline {
    agent none
        stage('Back-end') {
            agent {
                docker { image 'maven:3-alpine' }
            }
            steps {
                bat 'mvn --version'
            }
        }
}
