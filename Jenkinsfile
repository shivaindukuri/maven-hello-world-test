pipeline {
  agent {
    label 'Jenkins-slave'
  }
  stages {
    stage("checkout"){
      steps{
        checkout scm
      }
    }
    stage("Build"){
      steps{
        sh "mvn clean  install"
      }
    }
  }
}
