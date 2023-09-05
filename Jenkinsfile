pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/ravindra5765/tweet-trend-new.git'
            }
        }
    }
}
