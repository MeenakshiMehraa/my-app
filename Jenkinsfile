
node {
  stage('SCM Checkout'){
	  git 'https://github.com/MeenakshiMehraa/my-app'
  }
	stage ('Compile-Package'){
		//Get maven home path
   def mvnHome = tool name: 'maven3', type: 'maven'
		sh "${mvnHome}/bin/mvn -package"
   }
}

