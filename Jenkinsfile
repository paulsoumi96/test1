node { 
	 def mvn1
	stage ('Checkout Code')
		{
			checkout scm
			workspace = pwd() 
	    		 sh "ls -lat"
			  mvn1 = tool 'MAVEN_HOME'
   }
stage ('Build') {
       sh "'${mvn1}/bin/mvn' -Dmaven.test.failure.ignore clean package"
   }

}

}
       }
       }
