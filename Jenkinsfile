pipeline {
  agent any

  stages{
    stage('Build') {
      steps {
        echo "Building maven project"
        sh 'mvn install'
      }
      tools {
         maven 'Maven 3.8.6'
      }
    }
  }
}