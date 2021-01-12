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
                sh 'cd /home/ivan/site/porfolio'
            }
        }

        stage("pwd") {

            steps {
                sh 'pwd'
            }
        }
    }
}
