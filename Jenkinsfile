pipeline {
  agent any
  stage {
    stage ('Build') {
      echo 'Running Build automation'
      sh './gradlew build --no-deamon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
}
