pipeline{
 tools{
        jdk 'JAVA_HOME'
        maven 'M2_HOME'
    }
     agent { label 'windows'}
	  
	  stages{
	  
	  stage("checkout"){
	   steps{
	   git 'https://github.com/ashisnishanka/maven-project-17.git'
	   }
	                  }
	  stage("compile"){
	   steps{
	      sh 'mvn compile'
	   }
	                  }
	  
}
}
