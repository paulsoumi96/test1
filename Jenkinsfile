node {
   def gr
   def app
   stage('Checkout') { 
      git 'https://github.com/paulsoumi96/test.git'
      gr = tool 'gradle'
   }
   
stage ('Build') {
      // sh "'${mvn1}/bin/mvn' -Dmaven.test.failure.ignore clean package"
   sh 'gr build --info'
   }
}
