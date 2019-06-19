pipeline {
    agent {
       label ‘LinuxEnv’
        customWorkspace "${env.JOB_NAME}/${env.BUILD_NUMBER}"
    }
    stages {
        stage('Build') { 
            steps {
                println "Build" 
            }
        }
        stage('Test') { 
            steps {
                println "Test" 
            }
        }
        stage('Deploy') { 
            steps {
                println "Deploy" 
            }
        }
    }
}
