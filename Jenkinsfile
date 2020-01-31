pipeline {
  agent { docker { image 'maven:3.3.3' } }
  stages {
    checkout scm
    stage ('build') {
      steps {
        sh 'mvn --version'
      }
    }
  }
}
