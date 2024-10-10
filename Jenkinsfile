pipeline {
    agent any

    stages {
        stage("Maven Build") {
            when{
                branch 'develop'
            }
            steps {
                echo "Maven Build..."
            }
        }
        stage("Sonar Analysis") {
            when{
                branch 'develop'
            }
            steps {
                echo "Sonar Analysis..."
            }
        }
        stage("Vulnarability scanning") {
            when{
                branch 'develop'
            }
            steps {
                echo "Vulnarability scanning..."
            }
        }
        stage("Dev deploy") {
            when{
                branch 'develop'
            }
            steps {
                echo "Dev deploy..."
            }
        }
        stage("Test deploy") {
            when{
                branch 'test'
            }
            steps {
                echo "Test deploy..."
            }
        }
        stage("Prod deploy") {
            when{
                branch 'master'
            }
            steps {
                echo "Prod deploy..."
            }
        }
    }
}

  
