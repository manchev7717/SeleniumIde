pipeline {
    agent any
        stages {
            stage('Build App') {
                steps {
                   bat 'dotnet build'
                }
            }
            stage('Run Tests') {
                steps {
                    bat 'dotnet test'
                }
            }
        }
}
