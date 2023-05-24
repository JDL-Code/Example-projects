// Jenkinsfile
pipeline {
    agent any
    stages {
        stage('list file') {
            steps { 
                sh 'ls -l'
            }
        }
        stage('Show index.js') {
            steps { //ในโปรเจคต้องมี index.js
                echo "Hello Jenkins!"
            }
        }
    }
}
