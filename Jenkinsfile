pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                parameters {
                    string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
                    string(name: 'PERSON2', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
                    string(name: 'PERSON3', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
                }
            }
        }
    }
}
