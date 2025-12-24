pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main', url: 'https://github.com/Vuthyzzz/my-website001.git'
            }
        }

        stage('Build') {
            steps {
                echo 'No build needed for HTML'
            }
        }

        stage('Test') {
            steps {
                echo 'No tests yet'
            }
        }

        stage('Deploy') {
            steps {
                sh 'sudo cp -r * /var/www/html/'
            }
        }
    }
}