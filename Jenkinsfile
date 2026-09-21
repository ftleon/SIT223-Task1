pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Description: Compiles and packages the code.'
                echo 'Tool: Maven Test video'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Description: Runs unit tests to ensure code functions as expected, and integration tests to ensure components work together.'
                echo 'Tools: JUnit (Unit) and Postman (Integration)'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Description: Analyzes the code to ensure it meets industry standards.'
                echo 'Tool: SonarQube'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Description: Performs a security scan on the code to identify any vulnerabilities.'
                echo 'Tool: Snyk'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Description: Deploys the application to a staging server (e.g., AWS EC2 instance).'
                echo 'Tool: AWS CodeDeploy'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Description: Runs integration tests on the staging environment to ensure the application functions as expected in a production-like environment.'
                echo 'Tool: Selenium'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Description: Deploys the application to a production server (e.g., AWS EC2 instance).'
                echo 'Tool: AWS CodeDeploy'
            }
        }
    }
}
// test trigger for video
