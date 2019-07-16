node {
  stage ('Checkout') {
	git url: 'https://github.com/YmkSun/simple-java-maven-app.git'
  	stage 'Build'
		sh 'mvn --version'
		sh 'mvn clean verify'
	stage 'Test'
		sh 'echo "Hello World"'
  }
}