node {
  stage ('Checkout') {
	git url: 'https://github.com/YmkSun/simple-java-maven-app.git'
  	stage 'Build'
		sh 'java -version'
		sh 'echo "Build"'
	stage 'Test'
		sh 'echo "Hello World"'
  }
}