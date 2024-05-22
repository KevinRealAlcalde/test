pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World 3'
                sh 'ls'
                archiveArtifacts artifacts: '*', followSymlinks: false
                sh 'ls'
            }
        }
    }
}
