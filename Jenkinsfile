pipeline {
    agent any
    tools {
        maven 'M2_HOME'
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sleep 5
            }
        }
        stage('build') {
            steps {
                echo 'Hello World'
                sh 'mvn clean'
                sh 'mvn install"
                sh 'mvn package'
            }
        }
    stage('deploy') {
            steps {
                echo 'Hello World'
                sleep 5            
            }
        }
    stage('test') {
            steps {
                echo 'Hello World'
                sleep 5
            }
        }
    }
}


