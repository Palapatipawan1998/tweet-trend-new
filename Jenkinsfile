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
         stage('clofne') {
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
