pipeline {
    agent any

    stages {
        stage('Clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/sami1895/tweet-trend.git'
            }
        }
    }
}
