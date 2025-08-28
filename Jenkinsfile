pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo "Hello Build Stage"
                sh 'hostname'
            }
        }
     stage('test') {
            steps {
                echo "Hello tset Stage"
                sh 'pwd'
            }
        }     
    }
}
