pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Task: Compile and package the application code'
                echo 'Tool: Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Task: Run unit tests and integration tests'
                echo 'Tool: JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Task: Analyse source code quality and coding standards'
                echo 'Tool: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Task: Scan the application for security vulnerabilities'
                echo 'Tool: Snyk'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Task: Deploy the application to a staging environment'
                echo 'Tool: AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Task: Test the application in the staging environment'
                echo 'Tool: Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Task: Deploy the tested application to the production environment'
                echo 'Tool: AWS EC2'
            }
        }
    }
}
