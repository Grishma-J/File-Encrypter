pipeline {
    agent { label 'agent' }

    stages {
        stage('Build') {
            steps {
                sh '''
                echo "Running on Agent Node"
                echo "Hostname:"
                hostname
                echo "Node Name:"
                echo $NODE_NAME
                '''
            }
        }
    }
}
