pipeline {
    agent any

    stages {
        stage('Récupérer le code source') {
            steps {
                // Récupérer le code source depuis le référentiel Git
                git branch : 'main',
                url : 'https://github.com/AbirAyari1/PipeLineRepo.git'
            }
        }

        stage('Afficher la date système') {
            steps {
                // Afficher la date système
                sh 'date'
            }
        }
    }
}

         
   
