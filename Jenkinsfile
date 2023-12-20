pipeline {
    agent any
    
    stages {
        stage('build') {
            triggers {
                cron('* * * * *') // Déclencheur toutes les minutes pour cette étape
            }
            steps {
                echo 'build the app..'
                echo 'ap construit '
            }
        }
        
        stage('test') {
            steps {
                echo 'test th app ..'
            }
        }
        
        stage('deploy') {
            steps {
                echo 'deploy the app..'
            }
        }
    }
    
}
