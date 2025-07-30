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
                anyOf {

                    //anyofbelow condition is satisfied it will pass 
                    branch 'production' 
                    environment name: 'Proddeploy', value: 'Production'
                }
            }

            steps {

                echo "************ Deploying to Production *************"
            }
        }
    }
}
