pipeline{
  // agent{
  //   docker{
  //     image 'ruby'
  //   }
  // }
  agent any

  stages{
   
    stage('Build'){
      steps
      {
        echo " Build"
      sh 'bundle install'
      }
    }
    
  }
}