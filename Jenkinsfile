pipeline {
  agent any
       tools {
           maven 'Maven 3.8.6'
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