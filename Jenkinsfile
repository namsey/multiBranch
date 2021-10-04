pipeline {
  agent any 
  stages{
    stage("Checkout") {
      step{
            git 'https://github.com/namsey/multiBranch.git'
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
