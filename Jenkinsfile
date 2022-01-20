pipeline {
    agent any
    triggers {
        cron('H 4/* 0 0 1-5')
    }
    stages {
        stage('build') {
            steps {
                echo 'This Show Periodic Builds'
            }
        }
    }
}
