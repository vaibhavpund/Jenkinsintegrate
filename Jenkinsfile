pipeline {
    agent any
    triggers {
        cron('*/5 * * * *')
    }
    stages {
        stage('build') {
            steps {
                echo 'This Show Periodic Builds'
            }
        }
    }
}
