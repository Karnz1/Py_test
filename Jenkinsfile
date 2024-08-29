pipeline {
    agent {
        node {
            label 'docker-agent-py'
        }
    }

    stages {
        stage('run script') {
            steps {
                python3 app.py
            }
        }
    }
}
