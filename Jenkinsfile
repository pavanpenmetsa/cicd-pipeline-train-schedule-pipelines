pipeline {
  agent any
  stages {
    stage ('stage 1') {
      steps {
        echo 'Running build automation !!'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
