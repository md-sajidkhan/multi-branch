pipeline{
  agent any

  stages{
    stage('Listing Files'){
      steps{
        sh "ls -lrt"
      }
    }
    stage('Read Message'){
      steps{
        sh "cat Welcome.txt"
      }
    }
  }
}
