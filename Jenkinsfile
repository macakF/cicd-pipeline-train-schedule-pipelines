pipeline{
  agent any
  stages {
    stage ('build') {
      steps {
        echo 'runnung build automation'
        sh './gradle build --no-deamon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
