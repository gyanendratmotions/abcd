pipeline {
    agent any

    stages {
        stage("Checkout") {
            steps {
                git url: 'https://github.com/gyanendratmotions/abcd.git'
            }
        }
        stage("Docker Build") {
            steps {
                sh 'docker build -t myapp .'
            }
        }
    }
}
