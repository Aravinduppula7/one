 stages {
        stage('clone scm stage') {
            steps {
                echo 'clomg git aravind file name one repo '
                git 'https://github.com/wakaleo/game-of-life.git'
            }
        }
        
        stage('mvn') {
            steps {
                echo 'war.file '
               sh 'mvn clean install'
            }
        }
        
    }
}
