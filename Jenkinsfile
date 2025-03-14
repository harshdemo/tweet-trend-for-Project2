pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone code') {
            steps {
                git branch: 'main', url: 'https://github.com/harshdemo/tweet-trend-for-Project2.git'
            }
        }
    }
}