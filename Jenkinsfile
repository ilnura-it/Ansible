pipeline {
    agent any

    stages {

        stage('Terraform init') {
         steps {
            sh "echo 'Terraform init'"
         } 
        }

        stage ("Terraform plan") {
         steps {
            sh "echo 'Terraform plan'"
         } 
    }
        stage('Terraform Apply'){
         steps {
            sh "echo 'terraform apply'"
            }
        }
    }
}