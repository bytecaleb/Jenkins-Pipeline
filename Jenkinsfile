pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the code using Maven to compile and package the application.'
                echo 'Tool: Maven'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit tests with JUnit and integration tests with Selenium.'
                echo 'Tools: JUnit, Selenium'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Analysing code quality against industry standards.'
                echo 'Tool: SonarQube'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Scanning code for vulnerabilities.'
                echo 'Tool: OWASP Dependency-Check'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying the application to a staging server (AWS EC2).'
                echo 'Tool: AWS CLI'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests in the staging environment.'
                echo 'Tool: Postman / Newman'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploying the application to production (AWS EC2).'
                echo 'Tool: AWS CLI'
            }
        }
    }
}
