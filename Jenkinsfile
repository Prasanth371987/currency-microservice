pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
                retry(3) {
                echo "Print a message"
                error "this will give some error"
                }
                echo "********* Retried 3 times **********"
            }
        }
    }
}
