pipeline {
  agent any
       tools {
           maven '3.8.6'
        }
  stages{
    stage('Build') {
      steps {
        echo "Building maven project"
        sh 'mvn install'
      }

    }
  }
}