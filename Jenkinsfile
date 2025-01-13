pipeline {
  agent any
  stages{
    stage('Build'){
      steps{
        echo 'Fake build stage'
        bat "pwd"
      }
    }
    stage('Test'){
      steps{
        echo 'Fake test stage'
        bat "ls"
      }
    }
    stage('Deploy'){
      steps{
        echo 'Fake deploy stage'
        bat "touch newFile.txt"
      }
    }
  }
}
