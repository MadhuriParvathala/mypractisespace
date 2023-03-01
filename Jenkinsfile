pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'application is building'
            }
        }
        stage('testing') {
            steps {
                echo 'Automation testing'
            }
        }
        stage('UAT') {
            steps {
                echo 'waiting for UAT'
            }
        }
        stage('release') {
            steps {
                echo 'app is ready to release to prod services'
            }
        }
    }
}
