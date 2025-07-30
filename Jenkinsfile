//class 30

pipeline {
    agent any

    environment {
        Proddeploy = 'Production'
    }

    stages {
        stage ('ProdDeploy')
        {
            when {
                allOf {
                    branch 'main'
                    environment name: 'Proddeploy', value: 'Production'
                }
            }

            steps {

                echo "************ Deploying to Production *************"
            }
        }
    }
}
