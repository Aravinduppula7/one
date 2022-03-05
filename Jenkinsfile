
pipeline {
    agent any

    stages {
        stage('clone scm stage') {
            steps {
                echo 'clomg git aravind file name one repo '
                git branch: 'main', credentialsId: 'aravindgithub', url: 'https://github.com/Aravinduppula7/one.git'
            }
        }
        
        stage('list of git') {
            steps {
                echo 'all '
                sh 'ls -lrth'
            }
        }
    }
}
