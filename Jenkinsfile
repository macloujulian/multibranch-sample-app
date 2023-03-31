pipeline {
    agent any
	options{
		builDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumKeepStr: '5', daysToKeepStr: '5')
		disableConcurrentBuilds()
	}
    stages {
        stage('Hello') {
            steps {
                echo "Hola Mundo"
            }
        }
    }
}
