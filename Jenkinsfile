node {
  stage ('Checkout') {
  
  	stage 'Build'
	sh 'make all'
	stage 'Test'
  	sh 'make test'
  }
}