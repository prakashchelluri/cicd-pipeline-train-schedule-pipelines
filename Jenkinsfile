pipeline {
 agent any
  stages {
    stage {'build'} {
      steps {
        echo 'RUnning build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainschedule.zip'

      }
    }
  }
}
