pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code from GitHub...'
            }
        }
        stage('Build') {
            steps {
                echo 'Since this is simple HTML, no compilation is needed.'
                sh 'ls -ltr'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to web server directory...'
                // Example command to move files to an Apache/Nginx folder
                // sudo cp index.html /var/www/html/
            }
        }
    }
}
