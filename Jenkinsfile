create maven jenkins file for this pipeline {
    agent any

    stages {
        stage('Build stage') {
            steps {
                echo 'Building project…'
                // Add actual build commands here, e.g., 
                // sh 'mvn clean package'
            } 
        }

        stage('Test stage') {
            steps {
                echo 'Testing project…'
                // Add actual test commands here, e.g.,
                // sh 'mvn test'
            }
        }

        stage('Deploy stage') {
            steps {
                echo 'Deploying project…'
                // Add actual deployment commands here, e.g.,
                // sh 'deploy.sh'
            }
        }
    }
}
