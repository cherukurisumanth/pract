pipeline {	 
	agent any
		tools {
    maven 'maven-3.6.3'
		}
    	stages {     	 
    	stage("Compile") {          	 
            	steps {               	 
                	sh "mvn compile"          	 
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {               	 
                	sh "mvn test"          	 
            	}     	 
        	}	 
		stage("deploy") { 
			steps {
				sh "mvn deploy"
				//there are steps here  
			}       	 
		}
	}
}

