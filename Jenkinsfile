pipeline {
    agent {
        node {
            label 'maven'
        }
    }
environment {
    PATH = "/opt/apache-maven-3.9.9/bin:$PATH"
}
    stages {
        stage('build') {
            steps {
                echo "-------------build started------------------"
                sh 'mvn clean deploy -Dmaven.test.skip=true' //-Dmaven.test.skip=true
                echo "------------buildc completed------------------"
            }
        }
        
        
    }
}