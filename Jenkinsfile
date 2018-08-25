pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation con BIllY and JASPER' 
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
