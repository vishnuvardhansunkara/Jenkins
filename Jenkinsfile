pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/vishnuvardhansunkara/Jenkins.git', branch: 'main'
            }
        }
        stage('Run Script') {
            steps {
                sh '''
                echo "Hello, Jenkins!"
                echo "This is a sample script."
                '''
            }
        }
    }
}
