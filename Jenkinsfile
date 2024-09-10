pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                script {
                    def sleepTime = new Random().nextInt(11) + 5 // Aleatorio entre 5 y 15 segundos
                    bat "echo Stage: Checkout"
                    bat "echo Sleeping for ${sleepTime} seconds"
                    sleep sleepTime
                }
            }
        }
        stage('Build') {
            steps {
                script {
                    def sleepTime = new Random().nextInt(11) + 5
                    bat "echo Stage: Build"
                    bat "echo Sleeping for ${sleepTime} seconds"
                    sleep sleepTime
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    def sleepTime = new Random().nextInt(11) + 5
                    bat "echo Stage: Test"
                    bat "echo Sleeping for ${sleepTime} seconds"
                    sleep sleepTime
                }
            }
        }
        stage('Scan') {
            steps {
                script {
                    def sleepTime = new Random().nextInt(11) + 5
                    bat "echo Stage: Scan"
                    bat "echo Sleeping for ${sleepTime} seconds"
                    sleep sleepTime
                }
            }
        }
        stage('Package') {
            steps {
                script {
                    def sleepTime = new Random().nextInt(11) + 5
                    bat "echo Stage: Package"
                    bat "echo Sleeping for ${sleepTime} seconds"
                    sleep sleepTime
                }
            }
        }
        stage('Build Image') {
            steps {
                script {
                    def sleepTime = new Random().nextInt(11) + 5
                    bat "echo Stage: Build Image"
                    bat "echo Sleeping for ${sleepTime} seconds"
                    sleep sleepTime
                }
            }
        }
        stage('Publish Image') {
            steps {
                script {
                    def sleepTime = new Random().nextInt(11) + 5
                    bat "echo Stage: Publish Image"
                    bat "echo Sleeping for ${sleepTime} seconds"
                    sleep sleepTime
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    def sleepTime = new Random().nextInt(11) + 5
                    bat "echo Stage: Deploy"
                    bat "echo Sleeping for ${sleepTime} seconds"
                    sleep sleepTime
                }
            }
        }
        stage('Post-Deploy Tests') {
            steps {
                script {
                    def sleepTime = new Random().nextInt(11) + 5
                    bat "echo Stage: Post-Deploy Tests"
                    bat "echo Sleeping for ${sleepTime} seconds"
                    sleep sleepTime
                }
            }
        }
    }
}
