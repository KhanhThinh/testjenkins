pipeline {
    agent any

    stages {
        stage('Hello') {
            tools {
                terraform 'terraform'
            }
            steps {
                echo 'Hello World'
                echo 'Hello World 222'
                sh 'terraform -v'
            }
        }
    }
}
