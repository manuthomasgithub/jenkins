pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo "building" >> /var/www/html/index.html
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                echo "Testing.." >> /var/www/html/index.html
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                echo "Deploying...." >> /var/www/html/index.html
            }
        }
    }
}
