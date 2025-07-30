//class 30

pipeline {
    agent

    environment {
        ProdDeploy = 'Production'
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
        }
    }
}
