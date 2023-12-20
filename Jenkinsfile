pipeline {
    agent any
        options {
        cron('* * * * *') // Déclencheur toutes les minutes pour toute la pipeline
    }
    stages {
        stage('build') {
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
