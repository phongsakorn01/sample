pipeline {  
 agent any  
 environment {  
  dotnet = 'dotnetsdk'  
 }  
 stages {  
  stage('Build') {  
    steps {  
      bat 'dotnet build' 
   }  
  }  
  stage('Test') {  
    steps {  
      bat 'dotnet test' 
   }  
  }  
 
  
 
  
    }
 }
