pipeline {	 
    agent any	 
   	 stages {     	 
   	 stage("Compile") {          	 
   			 steps {               	 
   				  "mvn compile"   
                 echo "mvn compile"
   			 }     	 
   		 }     	 
   	 stage("Unit test") {          	 
   		 steps {             
             echo "mvn test"
   			 sh "mvn test"          	 
   			 }     	 
   		 }	 
   	 }
}

