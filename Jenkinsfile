pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from your Git repository
                git 'https://github.com/MysticDarknes/jenkins.git'
            }
        }

        stage('Build') {
            steps {
                // You can add build steps here if needed
            }
        }

        stage('Deploy') {
            steps {
                // Copy the HTML file to the desired location on your local machine
                sh 'cp index.html /var/www/html/'
            }
        }
    }
}
