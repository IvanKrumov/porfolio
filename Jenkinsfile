pipeline {
    
    agent any

    stages {

        stage("build") {

            steps {
                echo 'building the application...'

            }
        }

        stage("cd dir") {

            steps {
                sh 'cd /'
                sh 'ls'
            }
        }

        stage("pwd") {

            steps {
                sh 'pwd'
            }
        }
    }
}
