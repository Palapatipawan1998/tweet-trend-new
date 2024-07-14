pipeline {
    agent {
        node{
            label 'maven'
        }
    }

    stages {
        stage('clone code') {
            steps {
                sh 'mvn clean deploy'
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
