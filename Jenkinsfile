pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                 writeFile file: "/var/www/html/index.html", text: "This file is useful, need to archive it."
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
