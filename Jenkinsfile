pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                sh 'mvn clean deploy'
            }
        }
    }
}
