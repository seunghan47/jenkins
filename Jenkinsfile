pipeline {
    agent any
    stages {
        stage('Building npm file') {
            steps {
                echo "bilding npm file"
                sh 'npm run build'
            }
        }
        stage('Pushing to s3 bucket') {
            steps {
                echo "push to s3 bucket"
                // sh 'aws s3 copy /npmBiuld'
            }
        }
    }
}