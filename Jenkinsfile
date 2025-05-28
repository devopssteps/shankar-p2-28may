pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/devopssteps/shankar-p2-28may.git'
            }
        }
    }
}
