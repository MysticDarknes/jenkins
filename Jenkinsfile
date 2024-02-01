pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from your Git repository
                git branch: 'main', url: 'https://github.com/MysticDarknes/jenkins.git'
            }
        }

        stage('Deploy') {
            steps {
                // Copy the HTML file to the desired location on your local machine
                echo 'build and deploy steps go here'
                //sh 'cp index.html /var/www/html'  // Adjust the path accordingly
            }
        }
    }
}
