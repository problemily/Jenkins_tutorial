pipeline {
  agent any
  stages{
    stage('Build'){
      steps{
        echo 'Fake build stage'
        sh "pwd"
      }
    }
    stage('Test'){
      steps{
        echo 'Fake test stage'
        sh "ls"
      }
    }
    stage('Deploy'){
      steps{
        echo 'Fake deploy stage'
        sh "touch newFile.txt"
      }
    }
  }
}
