node {
	stage('SCM Checkout') {
		git 'https://github.com/mangeshdevops/my-app.git'
	}
	stage('Compile Package') {
		sh 'mvn package'
	}
}
