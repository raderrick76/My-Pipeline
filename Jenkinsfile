/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
   // environment {
   //   NEW_VERSION = '1.3.0'
   // }
    //parameters {
    //    choice(name: 'VERSION', choices: ['1.1.0', '1.2.0', '1.3.0'], description: '')
    //    booleanParam(name: 'executeTests', defaultValue: true, description:'')
    //}
    stages {
        stage('build') {
           // when {
           //     expression {
           //         params.executeTests
           //     }
            //}
            steps {
                echo 'build the application'
                //ech "building version ${NEW_VERSION}"
            }
        }
        stage('test') {
            steps {
                echo 'testing the application'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying the application'
               // echo "deploying version ${params.VERSION}"
            }
        }
    }
}
