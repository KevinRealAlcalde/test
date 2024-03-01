pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World 2'
                ls
                archiveArtifacts artifacts: '*', followSymlinks: false
                ls
            }
        }
    }
}
