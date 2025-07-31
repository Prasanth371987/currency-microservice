pipeline {
    agent any

    stages {
        stage ('build'){
            steps {
                echo "building the application"

            }

        }

        stage ('SONARSCANS') {
            steps {
                echo "SONAR is executing"
                sleep 15
            }
        }
       stage ('Fortify SCANS') {
            steps {
                echo "Fortify is executing"
                sleep 15 
    }
}
         stage ('Prisma SCANS') {
            steps {
                echo "Prisma is executing"
                sleep 15 

            }
         }
    }
}
