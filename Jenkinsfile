pipeline {
	agent any
	
	tools {
		maven 'Apache Maven 3.9.1'
	}
	
	stages {
		stage('Code Clone') {
			steps {
				git branch: 'main', credentialsId: 'Mahi', url: 'https://github.com/Mahi8817/Mahi.git'
			}
			
			
			}
			}
			stage('Code Clean') {
				steps {
					sh 'mvn clean'
				
			
			}
			}
			