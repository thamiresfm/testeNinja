pipeline{
  // agent{
  //   docker{
  //     image 'ruby'
  //   }
  // }
  agent any

  stages{
    step
    stage('Build'){
      step
      {
        echo " Build"
      sh 'bundle install'
      }
    }
        stage('Test'){
      step
      {
        echo " Test"
 
      }
    }
        stage('UAT'){
      step
      {
        echo " UAT"
     
      }
    }    stage('Prod'){
      step
      {
        echo " Prod"
 
      }
    }
    
  }
}