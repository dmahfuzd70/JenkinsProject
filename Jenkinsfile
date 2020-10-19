node{
   stage('SCM Checkout'){
     git 'https://github.com/dmahfuzd70/JenkinsProject'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'maven-3.6.3', type: 'maven'  
      sh "${mvnHome}/bin/mvn package"
   }
}
