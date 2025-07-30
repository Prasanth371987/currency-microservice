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
                steps {
                    echo "Welcome ${name}"
                    echo "You enrolled to ${course}"
                }
            }
        }
    }
