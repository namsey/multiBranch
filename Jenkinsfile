pipeline {
  agent any 
  stages{
    stage("One") {
      step{
            echo "Hello"
          }
  }
  stage("for dev branch"){
  when {branch "dev"}
    step {
          echo "hello dev"
         }
  }
  stage("for prod branch"){
  when {branch "prod"}
    step {
           echo "hello prod"
         }
 }
}
