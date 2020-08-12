pipeline{
  agent{
    docker{
      image 'ruby'
    }
  }
 

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