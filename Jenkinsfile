pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        withMaven(globalMavenSettingsConfig: '1') {
          sleep 10
        }

      }
    }
  }
}