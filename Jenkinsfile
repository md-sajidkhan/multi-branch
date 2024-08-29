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
    stage('Print Branch'){
      steps{
	echo "${GIT_BRANCH} and ${GIT_COMMIT}"
      }
    }
  }
}
