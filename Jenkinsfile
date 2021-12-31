node{
   stage('SCM Checkout'){
     git 'https://github.com/Elavarasi12/my-app'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'maven-3', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }

}
