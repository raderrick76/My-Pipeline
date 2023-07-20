/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    environment {
      NEW_VERSION = '1.3.0'
    }
    
    stages {
        stage('build') {
            steps {
                echo 'build the application'
                ech "building version ${NEW_VERSION}"
            }
        }
        stage('test') {
            steps {
                echo 'testint the application'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying the application'
            }
        }
    }
}
