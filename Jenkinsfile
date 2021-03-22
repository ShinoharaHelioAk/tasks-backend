pipeline {
    agent any
    stages {
        stage ('Build Backend') {
			steps {
				script 'mvn clean package -DskipTests=true'
			}
        }
    }
}