pipeline {
    agent any
    stages {
        stage ('Build Backend') {
			steps {
				bat script 'mvn clean package -DskipTests=true'
			}
        }
    }
}