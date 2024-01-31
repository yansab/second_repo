properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'fsutil volume diskfree C:\\'
            }
        }
    }
}
