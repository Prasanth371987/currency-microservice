//class 31

pipeline {
    agent any

    parameters {
        string(name: 'APPLICATION_NAME', description: 'Enter your application name', defaultValue: 'i27app')
        booleanParam(name: 'RUN_TESTS', description: 'Would you like torun tests', defaultValue: true)
        choice(name: 'ENV', description: 'Which environment we are deploying?', choices: ['dev','test','prod'])
        password(name: 'PASSWORD', description: 'Enter a password', defaultValue: 'SECRET')
    }

    stages {
        stage ('parameters example') {
            steps {

                echo "My application name is : ${params.APPLICATION_NAME}"
                echo "Are tests running ? ${params.RUN_TESTS}"
                echo " WHich environment deployment is going on ${params.ENV}"
                echo "what is the password ${params.PASSWORD}"

            }
        }
    }
}
