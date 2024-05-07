pipeline {
    agent any
    
    stages {
        stage('Clone project') {
            steps {
                // Clone the repository with branch specified
                git branch: 'main', url: 'https://github.com/dihson103/testcicd.git'
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
