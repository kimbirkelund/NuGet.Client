#!groovy

pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello Jenkins!"'
                sh './build.sh'
            }
        }
    }
}