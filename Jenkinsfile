pipeline {
    agent {node 'master'}
    stages {
        stage('DEV') { 
            steps {
                echo "Hello World at the top!"
            }
        }
        stage('Test') { 
            steps {
                echo "Hello World at the top!"
            }
        }
        stage('Disabled Polling') { 
            steps {
                echo "Hello World at the top!"
            }
        }
        stage('Enabled Polling') { 
            steps {
                echo "After enabling the polling we need to run the pipeline manually one time."
            }
        }
    }
}
