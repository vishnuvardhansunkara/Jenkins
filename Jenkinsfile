pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/your-username/your-repository.git', branch: 'main'
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
