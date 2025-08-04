//calss 32

pipeline {
    agent any
    {
        stages {
            stage ('Deploy to Dev environemt') {
                steps {
                echo "Deploying to Dev Environment"
            }
        }
        
            stage ('Deploy to TST environemt') {
                steps {
                echo "Deploying to TST Environment"
            }
        }
        
            stage ('Deploy to REG environemt') {
                steps {
                echo "Deploying to REG Environment"
    }
            }

            stage ('Deploy to Prod environemt') {

                options {
                    timeout (time:300, unit: 'SECONDS')
                }
                input {
                    message "Doing Prod Deployments"
                    ok 'Yes'
                    submitters 'sivasre' //who want to approve for prod deployments
                }
                steps {
                echo "Deploying to Prod Environment"
}
            }
    }
    
}
}
