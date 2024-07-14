pipeline {
    agent {
        node{
            label 'maven'
        }
    }
environment {
    PATH = "/usr/lib/jvm/java-21-openjdk-amd64:$PATH"
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
