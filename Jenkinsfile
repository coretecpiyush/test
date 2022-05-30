pipeline {
    agent any

    stages {
        stage("build") {
            steps {
                pwd && echo "Building the application.."
            }
        }

        stage("Test") {
            steps {
                echo "Testing the application.."
            }
        }

        stage("Deploy") {
            steps {
                echo "Deploying the application.."
            }
        }
    }
}
