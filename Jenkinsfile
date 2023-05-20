// Powered by Infostretch 

timestamps {

node () {

	stage ('Java application/INIT/PR Job - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '693f9d78-1528-4086-9d50-cb6bd86ad431', url: 'https://github.com/Sivayogi007/git2603.git']]]) 
	}
	stage ('Java application/INIT/PR Job - Build') {
 			// Shell build step
sh """ 
echo $input1 
 """ 
	}
}
}
