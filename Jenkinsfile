pipeline {
    agent any 

    stages {
        stage ('Build') {
            steps {
                echo "building the application"
            }
        }

        stage ('Scans')
        {
            steps {
                echo "Performing sonar scans"
            }
        }
        stage ('dockerbuild')
        {
            steps {
                echo "Performing docker scans"
            }
        }
        stage ('devenv')
        {
            steps {
                echo "Performing devenv scans"
            }
        }
        stage ('stageenv')
        {
            steps {
                echo "Performing sonarstageenv scans"
            }
        }
        stage ('Prodenv')
        {
            steps {
                echo "Deploying Prod not triggered"
            }
        }
    }
}
