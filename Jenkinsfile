pipeline {	 
    agent any	 
   	 stages {     	 
   	 stage("Compile") {          	 
   			 steps {               	 
   				 sh "mvn compile"   
                 echo "mvn compile"
   			 }     	 
   		 }     	 
   	 stage("Unit test") {          	 
   		 steps {               	 
   				 sh "mvn test"          	 
   			 }     	 
   		 }	 
   	 }
}

