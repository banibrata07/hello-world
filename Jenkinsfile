pipeline {
	agent any
	tools {
		jdk  "JAVA_1.8"
		maven	"M2_HOME"
	}

	stages {
		stage(clone_resource){
			steps{
			git url: 'http://github.com/banibrata07/hello-world'
			}
		
		}
	}
}
