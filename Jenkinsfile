pipeline {
    agent any

    stages {
        stage('initialize') {
            steps {
                sh 'terraform init'
            }
        }
         stage('validate') {
            steps {
                sh 'terraform init'
            }
        }
         stage('plan') {
            steps {
                sh 'terraform plan'
            }
        }
         stage('apply') {
            steps {
                sh 'terraform apply --auto-approve'
            }
        }
         stage('destroy') {
            steps {
                sh 'terraform destroy --auto-approve'
            }
        }
    }
}
