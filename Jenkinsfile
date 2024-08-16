pipeline {
    agent any

    stages {
        stage('first') {
            steps {
                echo 'Hello World'
            }
        }
        stage(" code ") {
            steps {
                git " https://github.com/jagadish7-25/one.git"
            }
        }
        stage (" test ") {
            steps {
                sh "ps -ef "
            }
        }
        stage (" deploy") {
            steps {
                echo " hello world-2"
            }
        }
    }
}
