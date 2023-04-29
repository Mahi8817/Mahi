pipeline {
	agent any
	
	tools {
		maven 'maven'
	}
	
	stages {
		stage('Code Clone') {
			steps {
				git branch: 'main', credentialsId: 'Mahi', url: 'https://github.com/Mahi8817/Mahi.git'
			}
			
			
			}
			}
			stage ('Code Clean') {
				steps {
					sh 'mvn clean'
			}	
			
			}
			
			}