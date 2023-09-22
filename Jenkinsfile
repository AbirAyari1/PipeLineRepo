  pipeline {
  agent any
    stages {
      stage('Chekout GIT') {
        steps{
          echo 'Pulling...'
          git branch: 'main',
            url : 'https://github.com/AbirAyari1/PipeLineRepo.git'
            
        }
      }
     stage('Testing Maven')
      {steps {
        sh "mvn -verssion"
      }
      }
      
    }

    
  }
