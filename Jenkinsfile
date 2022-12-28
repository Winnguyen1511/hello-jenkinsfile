pipeline {
    agent any
    environment{
        BUILD_NUMBER = ${env.BUILD_NUMBER}
        PROJECT = ${params.PROJECT}
        BRANCH = ${params.BRANCH}
    }
    stages{
        stage('Build'){
            steps {
                dir('/var/jenkins_home/workspace/${BUILD_NUMBER}_${PROJECT}_${BRANCH}') {
                        git 'https://github.com/Winnguyen1511/hello-jenkinsfile.git'
                    }           
                }
            }
        }   
}