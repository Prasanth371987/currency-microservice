pipeline
 {
    agent any

    //environment variables

    environment {
        TODAYS_DAY = 'wednesday'
    }

    stages {
        stage('build stage') {

            when {

                environment name: 'TODAYS_DAY', value: 'wednesday'
            }
            steps {
                echo "executing pipeline for when example"
            }
        }
    }
 }
