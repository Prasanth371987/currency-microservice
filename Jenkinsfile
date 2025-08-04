//calss 32

pipeline {
    agent any
    
        stages {   
            stage('Build') {
            
                Steps {
                    echo "Building the application"
                }
            }
        }
        post {
            success {

                //code will trigger if the pipeline issuccess

                echo "POST ==============Success block is triggered"
            }
                failure {

                    //will trigger only if failure
                    echo "POST ============== Failure block is triggered"
                }
                    always {

                        //will trigger if failure/success
                        echo "POST ============== Always block is triggered"
                    }
                }
            }
        
