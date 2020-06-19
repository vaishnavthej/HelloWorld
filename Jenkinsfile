pipeline {
    agent any 
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'python3 --version'
                sh 'echo Vaishnav You are able run first jenkins job on your own'
            } 
        }
    }
post {
        always {
            echo 'This will always run'
        }
    }
}
