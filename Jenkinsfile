pipeline {  
 agent any  
 environment {  
  dotnet = 'dotnetsdk'  
 }  
 stages {  
  stage('Checkout') {  
   steps {
       git credentialsId: '8b73eb85-2957-4d29-8115-df34cd84f4cf', url: 'https://github.com/phongsakorn01/testjenkin.git', branch: 'main'
   }  
  }  
 stage('Build') {  
   steps {  
    bat 'dotnet build' 
   }  
  }  
 
  
 
  
    }
 }
