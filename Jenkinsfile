pipeline {
    agent any
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