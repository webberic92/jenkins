pipeline {
  agent any
  stages {
    stage('First Stage') {
      steps {
        echo 'Hello World'
      }
    }
    stage('Maven Build') {
      steps {
        sh 'mvn clean package -DskipTests'
      }
    }
  }
}