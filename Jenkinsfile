// Test using a sharedlib version that is not at HEAD

@Library('jenkins-sharedlib@ef3775150c6337e1165d6192d023f65749547109') _

pipeline {
    agent none
    stages {
        stage ('Test Stage') {
            steps {
                myprint('Hello')
            }
        }
    }
}
