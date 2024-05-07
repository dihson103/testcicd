pipeline {
    agent any

    stages {
        stage('Clone project') {
            steps {
                script {
                    // Define the repository URL
                    def repoUrl = 'https://github.com/dihson103/testcicd.git'
                    
                    // Define the branch to checkout (if needed)
                    def branch = 'main'
                    
                    // Clone the repository
                    checkout([$class: 'GitSCM', branches: [[name: branch]], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: repoUrl]]])
                }
            }
        }
        // Add more stages as needed
    }
    
    // Add post-build actions or notifications
    post {
        always {
            // Clean up workspace or perform other actions
        }
    }
}
