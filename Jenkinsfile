pipeline {
    agent none
    stages {
        stage ('pull code from git') {
            steps {
                build   job: 'fizzbuzz-pull-source-code'
            }
        }
    }
}