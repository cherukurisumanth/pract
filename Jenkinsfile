pipeline {	 
	agent any	 
    	stages {     	 
    	stage("Compile") {          	 
            	steps {               	 
                	bat "mvn compile"          	 
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {               	 
                	bat "mvn test"          	 
            	}     	 
        	}	 
		stage("deploy") { 
			steps {
				bat "mvn deploy"
				//there are steps here  
			}       	 
		}
	}
}

