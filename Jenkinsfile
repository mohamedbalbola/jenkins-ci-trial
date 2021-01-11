pipeline {
  agent any
  stages {
    stage('build the code') {
      steps {
        sh 'mvn clean package'
        echo 'this build was successfully build'
      }
    }

  }
}