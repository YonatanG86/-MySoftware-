pipeline {
    agent any
    triggers {
        cron('H/30 * * * *') // Runs the pipeline every 30 minutes
    }
    
    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/YonatanG86/-MySoftware-.git'
            }
        }
    }
}
