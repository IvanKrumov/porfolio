
pipeline {
    
    agent any

        stage("deploy") {

            steps {
                echo 'deploying the application...'
                cd /home/ivan/site/porfolio
                git pull https://github.com/IvanKrumov/porfolio.git
            }
        }
    }
}
