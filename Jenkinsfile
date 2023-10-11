pipeline{
  agent any
  stages{
    stage("Deploy"){
      steps{
        echo "Test successful"
        bat "mvn compile"
      }
    }
    
       stage("build"){
      steps{
        echo "build successful"
        bat "mvn clean"
      }
       }
    stage("Test"){
      steps{
        echo "Test successful"
        bat "mvn Test"
      }
       }
  }
