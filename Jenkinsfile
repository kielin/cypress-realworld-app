pipeline {
//     agent any
    agent {
        docker {
            image 'node:16-alpine3.15'
            args '-p 3000:3000'
        }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'PUPPETEER_SKIP_CHROMIUM_DOWNLOAD=true yarn install'
                echo 'Finished Built..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
//                 sh 'yarn dev'
                
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
