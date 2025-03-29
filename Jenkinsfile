pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/vishal307-ux/docker_jenkins_project'
            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
                // Add build commands here (e.g., mvn, npm, gradle)
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                // Add test commands here
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
                // Add deployment steps here
            }
        }
    }
}
