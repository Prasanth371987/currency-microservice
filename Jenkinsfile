//calss 32

pipeline {
    agent any
    
        stages {         
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
    

