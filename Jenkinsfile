pipeline{
  agent any
  stages{
    stage('Build'){
      step {
        echo 'Runing Buil automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
