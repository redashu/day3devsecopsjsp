pipeline {

agent any

tools {
	maven 'maven'

 }

stages {
	stage('checkcing maven installation'){
            steps {
			sh 'mvn -v'

		}
	}
	
	stage('security checking by trufflehog'){
		steps {
			sh 'docker run --rm ashu:secv1'
		
		
		 }
	
	
	
	}
	
	stage('build java project'){
		steps {
			sh 'mvn clean package'
		
		}
	
	}

 }

}
