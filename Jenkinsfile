pipeline{
    agent any
    parameters{
        string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should i say hello to?')
    }
    stages{
        stage('Example'){
            steps {
                echo "Hello ${params.PERSON}"
            }
        }
    }

}