pipeline {
    agent { docker { 
    	image 'maven:3.3.3' 
    	label 'docker_node'} }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}