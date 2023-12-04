pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                dir("Akshata_Shinde_RestfulAndSoapWS") {
		bat "mvn clean"
	}
            }
        }
        stage('Compile') {
            steps {
	dir("Akshata_Shinde_RestfulAndSoapWS") {
		bat "mvn compile"
	}
            }
        }
        stage('Test') {
            steps {
	dir("Akshata_Shinde_RestfulAndSoapWS") {
		bat "mvn test"
	}
            }
        }
        stage('Result') {
            steps {
                echo "Result"
            }
        }
    }
}