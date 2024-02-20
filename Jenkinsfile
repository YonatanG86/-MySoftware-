//properties([pipelineTriggers([pollSCM('H/2 * * * *')])])
pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // git branch: 'main', url: 'https://github.com/YonatanG86/-MySoftware-.git'
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/YonatanG86/-MySoftware-.git']])
            }
        }
    }
}
