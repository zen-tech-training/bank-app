pipeline {
	agent any
	stages {
		stage('Compile Java Program') {
			steps {
					javac Hello.java
			}
		}
		stage('Run Java Program') {
			steps {
					java Hello
			}
		}

	}
}
