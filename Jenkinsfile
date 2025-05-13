pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Stage: Build"
                echo "This stage compiles and packages the source code using Maven."
                echo "Tool: Maven"
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo "Stage: Unit and Integration Tests"
                echo "This stage runs unit tests to verify individual components, and integration tests to ensure components work together correctly."
                echo "Tool: JUnit"
            }
        }

        stage('Code Analysis') {
            steps {
                echo "Stage: Code Analysis"
                echo "This stage performs static code analysis to detect code smells, bugs, and ensure adherence to coding standards."
                echo "Tool: SonarQube"
            }
        }

        stage('Security Scan') {
            steps {
                echo "Stage: Security Scan"
                echo "This stage scans for known vulnerabilities in code or dependencies to ensure application security."
                echo "Tool: Snyk"
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo "Stage: Deploy to Staging"
                echo "This stage deploys the application to a staging server to simulate production."
                echo "Tool: AWS CLI"
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo "Stage: Integration Tests on Staging"
                echo "This stage re-runs integration tests in the staging environment to ensure deployment success."
                echo "Tool: Selenium"
            }
        }

        stage('Deploy to Production') {
            steps {
                echo "Stage: Deploy to Production"
                echo "This stage deploys the application to the live production environment."
                echo "Tool: AWS CLI"
            }
        }
    }
}
