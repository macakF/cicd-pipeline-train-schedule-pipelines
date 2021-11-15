pipeline{
  agent any
  stages {
    stage ('build') {
      steps {
        echo 'runnung build automation'
        sh './gradlew build'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
