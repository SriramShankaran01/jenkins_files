pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'webhook', url: 'https://github.com/SriramShankaran01/amma.git']])
            }
        }
    }
}
