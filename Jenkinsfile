
pipeline {
    agent any 

    tools {nodejs "node"}

    stages {

        stage ("build") {
            steps {
                echo 'building our app...'
                sh 'npm install axios'
            }
        }
        stage ("test") {
            steps {
                echo 'testing our app...'
            }
        }
        stage ("deploy") {
            steps {
                echo 'deploying our app...'
            }
        } 
    }
} 