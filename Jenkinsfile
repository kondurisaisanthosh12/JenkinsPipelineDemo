pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploying'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage(release) {
            steps {
                echo 'releasing'
            }
        }
    }
}
