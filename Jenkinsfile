pipeline {
    agent any

    stages {
        stage('run') {
            steps {
                sh "docker run -d ngnix:"${version}"
            }
      
    }
}
}
