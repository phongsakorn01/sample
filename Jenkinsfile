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
  stage('Publish') {  
    steps {  
      archiveArtifacts artifacts:'C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\testwin2\\bin\\Debug\\net7.0\\publish\\*.zip' 
   }  
  }  
  }
  
 
  
    
 }
