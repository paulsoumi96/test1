node {
   def mvn1
   def app
   stage('Checkout') { 
      checkout scm
      workspace = pwd ()
       sh 'ls -lat'
   }
   
stage ('Build') {
      // sh "'${mvn1}/bin/mvn' -Dmaven.test.failure.ignore clean package"
    sh 'gradle init'
      sh 'ls -lat'
   sh 'gradle build'
   }
}
