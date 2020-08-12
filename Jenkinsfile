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
        echo " Build or Resolver dependencies"
        sh 'bundle install'
      }
    }
       stage('Test'){
      steps
      {
        echo " Running regression test"
     
      }
    }
       stage('UAT'){
      steps
      {
        echo "Wait for User Acceptance"
        input(message: "Go to production", ok: 'Yes')

      }
    }
       stage('Prod'){
      steps
      {
        echo " WebApp is Ready"
     
      }
    }
    
  }
}