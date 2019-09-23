node { 
	 def mvn1
	stage ('Checkout Code')
		{
			checkout scm
			workspace = pwd() 
	    		 sh "ls -lat"
  		 }
        stage ('create war')
   	 {
    	mavenbuildexec "mvn build"
    	}

}
