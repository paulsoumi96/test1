node {
   
   stage('install gradle'){
   tool name: 'gradle', type: 'gradle'
   }
   stage('Checkout') { 
      checkout scm
      workspace = pwd ()
       sh 'ls -lat'
   }
   stage('Gradle initialization')}
      sh './gradlew init'
      echo "initialization complete"
   }
   stage ('Build') {
      // sh "'${mvn1}/bin/mvn' -Dmaven.test.failure.ignore clean package"  
   sh './gradlew build clean'
   }

}
