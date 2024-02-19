properties([pipelineTriggers([pollSCM('H/2 * * * *')])])
pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/YonatanG86/-MySoftware-.git'
            }
        }
    }
}
