pipeline {
  agent any
  
  stages {

    stage('confirm aws') {
      steps {
        withAWS(region:'us-west-2', credentials:'aws_pipeline') {
          sh 'aws --version'
        }
      }
    }    
    


  }
}
