pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation for Susanne'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
