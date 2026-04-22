pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building the project..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }
    }
}




pipeline {
    agent any

    stages {
        stage('Initialize') {
            steps {
                echo "Starting Pipeline..."
            }
        }

        stage('Build') {
            steps {
                echo "Building..."
            }
        }

        stage('Test') {
            steps {
                echo "Testing..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
            }
        }
    }
}

