pipeline {
  agent any
   tools {
      maven 'maven'
    }
  stages {
    stage('Load') {
      steps {
        sh "mvn verify -Pperformance"
      }
    }
  }
}
