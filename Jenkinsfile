pipeline {  
 agent any  
 environment {  
  dotnet = 'dotnetsdk'  
 }  
 stages {  
 
  stage('Build') {  
    steps {  
      bat 'dotnet build' 
      bat 'echo started'
      bat 'dotnet publish'
      
      
  }  }
 
  
    
 }}
