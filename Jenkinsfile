pipeline {
    agent any
    tools {
        nodejs '14.18.0'
    }

    options {
        timeout(time: 2, unit: 'MINUTES')
    }

    stages {
        stage('Install dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('run cow') {
            steps {
                sh 'node index.js'
            }
        }
        }
    }
    }
}