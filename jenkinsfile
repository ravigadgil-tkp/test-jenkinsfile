pipeline {
    agent any
    stages {
        stage('Build the project'){
            steps {
                sh "bash /share/jenkins-scripts/build/golang-staging.sh"
            }
        }

        stage('Deploy the job'){
            steps {
            	sh "bash /share/jenkins-scripts/deploy/golang-staging.sh"
            }
        }
    }
}
