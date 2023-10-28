pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                sh 'maven clean deploy'
            }
        }
    }
}
