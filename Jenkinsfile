pipeline {
  agent any
  stages {
    stage('build the code') {
      steps {
        sh 'mvn package -Dmaven.test.skip=true'
      }
    }

    stage('deploy to server') {
      steps {
        sh 'cp /var/lib/jenkins/workspace/ipeline-without-jenkinsfile_main/target/vprofile-v2.war /var/lib/tomcat9/webapps/ROOT.war'
      }
    }

  }
}