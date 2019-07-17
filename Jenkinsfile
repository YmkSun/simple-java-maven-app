pipeline {
	agent {
        docker {
            image 'maven:3-alpine' 
            args '-v C/Users/myokyaw.ye/.m2:C/Users/myokyaw.ye/.m2' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}