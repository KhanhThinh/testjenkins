pipeline {
    agent any

    stages {
        stage('Hello') {
            tools {
                terraform 'terraform'
            }
            steps {
                echo 'Hello World'
                sh 'terraform -v'
            }
        }
    }
}
