pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World 2'
                archiveArtifacts artifacts: '*', followSymlinks: false
            }
        }
    }
}
