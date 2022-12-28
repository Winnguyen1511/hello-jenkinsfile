pipeline {
    agent any
    stages{
        stage('Build'){
            steps {
                dir('/var/jenkins_home/workspace/${env.BUILD_NUMBER}_${params.PROJECT}_${params.BRANCH}') {
                        git 'https://github.com/Winnguyen1511/hello-jenkinsfile.git'
                    }           
                }
            }
        }   
}