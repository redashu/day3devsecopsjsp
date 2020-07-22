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
	
	stage('build java project'){
		steps {
			sh 'mvn clean package'
		
		}
	
	}

 }

}
