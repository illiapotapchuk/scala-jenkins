pipeline {
    agent {
        docker {
            image 'hseeberger/scala-sbt'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'sbt clean compile'
            }
        }
    }
}