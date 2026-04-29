pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Stage 1 - Build: Compiling and packaging the application using Maven build automation tool to generate deployable artifacts.'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2 - Testing: Running unit tests using JUnit to validate individual components and Selenium for integration tests to ensure modules work together correctly.'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Stage 3 - Code Analysis: Performing static code analysis using SonarQube to ensure code quality, maintainability, and adherence to industry standards.'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Stage 4 - Security Scan: Scanning dependencies and source code using OWASP Dependency-Check to identify known vulnerabilities and security risks.'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5 - Deploy to Staging: Deploying application to a staging environment hosted on AWS EC2 instance for pre-production validation.'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6 - Staging Tests: Running integration tests using Selenium on the staging environment to validate application behaviour in a production-like setup.'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Stage 7 - Deploy to Production: Deploying validated application to AWS EC2 production server for live user access.'
            }
        }
        stage('change Git'){
            steps{
                echo 'this is change trigger for the demo'
            }
    }
}

}
