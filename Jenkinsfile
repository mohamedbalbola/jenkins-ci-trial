pipeline {
  agent any
  stages {
    stage('build the code') {
      steps {
        sh 'mvn package -Dmaven.test.skip=true'
      }
    }

  }
}