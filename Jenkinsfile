//class 30

pipeline {
    agent

    environment {
        Proddeploy = 'Production'
    }

    stages {
        stage ('ProdDeploy')
        {
            when {
                allOf {
                    branch 'main'
                    environment name: 'ProdDeploy', value: 'Production'
                }
            }

            steps {

                echo "************ Deploying to Production *************"
            }
        }
    }
}
