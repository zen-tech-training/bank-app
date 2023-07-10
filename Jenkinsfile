pipeline {
	agent any
	stages {
		stage('Compile Java Program') {
			steps {
					bat "javac Hello.java"
			}
		}
		stage('Run Java Program') {
			steps {
					bat "java Hello"
			}
		}

	}
}
