stage ('Test - Checkout') {
    checkout(
	     [$class: 'GitSCM', branches: [[name: '*/master']], 
	      doGenerateSubmoduleConfigurations: false, extensions: [[$class: 'CleanBeforeCheckout', deleteUntrackedNestedRepositories: true], 
	       [$class: 'LocalBranch', localBranch: 'localbr']], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '9e3ee20f-af93-4b39-a6bb-72ffead1861c', url: 'https://github.com/kanitham/devlabs.git']]]
	   )
}
