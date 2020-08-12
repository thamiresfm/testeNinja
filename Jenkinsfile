pipeline{
  // agent{
  //   docker{
  //     image 'ruby'
  //   }
  // }
  agent any

  stages{
    stage('Build'){
      echo " Build"
      sh 'bundle install'
    }
    stage('Teste'){
      echo " Teste"
    }
    stage('UAT'){
      echo " UAT"
    }
    stage('Prod'){
      echo " Prod"
    }
  }
}