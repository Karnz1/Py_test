pipeline {
    agent docker-agent-python

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                python3 app.py
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
