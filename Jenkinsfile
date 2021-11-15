pipeline{
  agent any
  stages {
    stage ('build') {
      steps {
        echo 'runnung build automation'
        sh './gradlew bulid --no-deamon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
