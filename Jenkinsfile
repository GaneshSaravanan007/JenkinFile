pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'master',
                    credentialsId: 'gitPass',
                    url: 'https://github.com/GaneshSaravanan007/ShellScripts.git'
            }
        }
    }
}

