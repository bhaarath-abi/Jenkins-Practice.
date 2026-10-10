pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/bhaarath-abi/Jenkins-Practice..git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building project..."'
                sh 'ls -l'
                sh 'echo "Build complete!"'
            }
        }
    }
}
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/bhaarath-abi/<your-repo>.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building project..."'
                sh 'ls -l'
                sh 'echo "Build complete!"'
            }
        }
    }
}
