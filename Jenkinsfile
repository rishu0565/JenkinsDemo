pipeline {
  agent any
  stages {
    stage("1st Stage") {
      steps{
        sh "hostname"
      }
    }
    stage("Build the project") {
      steps{
        sh "mvn clean package"
      }
    }
    stage("3rd Stage") {
      steps{
        sh "echo hello"
      }
    }
  }
}
