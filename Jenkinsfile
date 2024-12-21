pipeline {
    agent any
    
    triggers {
        githubPush()
    }

    stages {
        stage('Hello World') {
            steps {
                echo 'Hello, World'!'
            }
        }
    }
}