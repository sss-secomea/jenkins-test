@Library('jenkins-sharedlib@ef3775150c6337e1165d6192d023f65749547109') _

pipeline {
    agent none
    triggers {
        pollSCM('H/10 * * * *')
    }
    stages {
        stage ('Test Stage') {
            steps {
                myprint('Hello')
            }
        }
    }
}
