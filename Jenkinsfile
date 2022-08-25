pipeline {
    agent any 
    stages {
        stage('Installing dependency') {
            steps {
                sh 'npm install' 
            }
        }
        stage('Build') {
            steps {
                sh 'npm run build' 
            }
        }
        stage('Publish Artifacts') {
            steps {
                echo 'Save the assemblies generated from the compilation' 
            }
        }
    }
}
