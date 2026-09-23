pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the code using Maven to compile and package the application.'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit tests with JUnit and integration tests with TestNG.'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Analysing code quality and standards using SonarQube.'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Scanning the code for vulnerabilities using OWASP Dependency-Check.'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying the application to a staging AWS EC2 instance using Ansible.'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on the staging environment using Postman/Newman.'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploying the application to a production AWS EC2 instance using Ansible.'
            }
        }
    }
}