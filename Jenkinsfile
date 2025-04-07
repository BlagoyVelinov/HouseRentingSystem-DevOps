pipeline {
    agent any
    stages {
        stage('Build Project') {
            steps {
                bat 'dotnet build'
            }
        }
        stage('Run dotnet tests') {
            steps {
                bat 'dotnet test'
            }
        }
        // stage('Approval for production Deployment') {
        //     steps {
        //         script {
        //             input message: 'Proceed with production deployment?', ok: 'Deploy'
        //         }
        //     }
        // }
    }
}
