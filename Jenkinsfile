pipeline {
    agent any
    stages {
        stage('build') {
            steps {

                   
                   input "Does the staging environment look ok?"

                sh 'python hello4.py'
            }
        }
    }
}