pipeline {
    agent any
    stages {
        stage('Git Jenkinsfile run') {
            steps {
                echo 'Running stage 1'
            }
        }
    }
    post {
        always {
            echo 'Always Running...'
        }
    }
}
