pipeline {
    agent {
        node{
            label 'maven'
        }
    }
environment {
    PATH = "/usr/share/maven:$PATH"
}

    stages {
        stage('build') {
            steps {
                sh 'mvn clean deploy'
            }
        }
         stage('cloooofne') {
            steps {
                echo 'hi'
            }
        }
         stage('cl0one2') {
            steps {
                echo 'hi'
            }
        }
    }
}
