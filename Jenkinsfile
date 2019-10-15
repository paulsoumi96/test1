node {
   def mvn1
   def app
   stage('Checkout') { 
      git 'https://github.com/paulsoumi96/test.git'
      mvn1 = tool 'MAVEN_HOME'
      sh 'graddle init'
      sh 'ls -lat'
   }
   
stage ('Build') {
      // sh "'${mvn1}/bin/mvn' -Dmaven.test.failure.ignore clean package"
   sh 'gradle build'
   }
}
