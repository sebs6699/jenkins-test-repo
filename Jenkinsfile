pipeline {
    agent any
    stages {
        stage('Show Info') {
            steps {
                script {
                    echo "Jenkins URL: ${env.JENKINS_URL}"
                    echo "Build ID: ${env.BUILD_ID}"
                }
            }
        }
    }
}
