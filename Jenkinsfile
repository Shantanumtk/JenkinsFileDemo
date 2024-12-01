pipeline {
    agent any  // This defines where the pipeline will run (any available agent)

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add build commands here (e.g., mvn clean install for a Java project)
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here (e.g., mvn test for a Java project)
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Add deploy commands here (e.g., scp, docker, kubectl, etc.)
            }
        }
    }
}
