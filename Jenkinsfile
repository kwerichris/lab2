pipeline {
  agent any

  stages{
    stage('Build') {
      steps {
        echo "Building maven project"
        sh 'mvn install'
      }
    }
  }
}