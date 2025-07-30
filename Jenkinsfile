pipeline {
    agent any 
        //

        //environment can be configured as pipeline level or stage level

        environment {

            //key =value ${key}

            name = "Prasanth"
            course = "Devops engineer program"
        }

        stages {
            stage ('Firststage') {
                environment {
                    cloud = "GCP"
                     name = "Mahesh"
                }
                steps {
                    echo "Welcome ${name}"
                    echo "You enrolled to ${course}"
                }
            }

            stage ('secondstage') {
                steps {
                    echo "Secondstage : Welcome ${name}"
                    echo "Secondstage : You enrolled to ${course}"
                    
                }
            }
        }
    }
