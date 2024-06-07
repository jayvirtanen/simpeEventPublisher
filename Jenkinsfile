pipeline {
    agent any

    stages {
        stage('Example') {
            steps {
                echo 'sending helloWorld'
                sh 'printenv'
                publishEvent simpleEvent('helloWorld')
            }
        }
    }
}
