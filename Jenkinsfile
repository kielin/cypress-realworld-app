pipelin {
    agent any

    stages {
        stage('init') {
            echo 'init'
            node {
                sh 'npm install'
            }
        }

        stage('test') {
            echo 'test'
            // node {
            //     sh ''
            // }
        }

        stage('deploy') {
            echo 'deploy'
        }
    }
}
