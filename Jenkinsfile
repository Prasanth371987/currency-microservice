//class 30

pipeline
 {
    agent any

    stages {
        stage('build stage') {

            when {
                expression { BRANCH_NAME ==~ /(prod|main)/ }
            }
        }
    }

 }
