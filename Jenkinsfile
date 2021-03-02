pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World INSIDE tutor'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again! INSIDE tutor'
        }
    }
}
