pipeline {
    agent {
        node{
            label 'maven'
        }
    }

    stages {
        stage('clone code') {
            steps {
                git branch: 'main', url: 'https://github.com/Palapatipawan1998/tweet-trend-new.git'
            }
        }
         stage('clone') {
            steps {
                echo 'hi'
            }
        }
         stage('clone2') {
            steps {
                echo 'hi'
            }
        }
    }
}
