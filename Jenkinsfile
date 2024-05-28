pipeline {
    agent any

    tools {
	maven "M2_HOME"
    }

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/vatsanTraining/docker-git-jenkins.git'
                dir('docker-git-jenkins'){
                        bat "mvn package"

                }

            }
        }
