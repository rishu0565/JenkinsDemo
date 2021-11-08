pipeline {
  agent any
  stages {
    stage("1st Stage") {
      steps{
        sh "hostname"
      }
    }
    stage("2nd Stage") {
      steps{
        sh "date"
      }
    }
    stage("3rd Stage") {
      steps{
        sh "echo hello"
      }
    }
  }
}
