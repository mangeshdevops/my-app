node {
	stage('SCM Checkout') {
		git 'git@github.com:mangeshdevops/my-app.git'
	}
	stage('Compile Package') {
		sh 'mvn package'
	}
}
