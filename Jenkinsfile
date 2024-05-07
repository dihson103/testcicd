pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/dihson103/testcicd.git'
                git 'https://github.com/dihson103/testcicd.git'
            }
        }
    }
}