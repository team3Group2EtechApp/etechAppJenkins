pipeline {
    agent any
        stages {
            stage('1-Phil'){
                steps {
                    sh 'ps -ef'
                    sh 'sudo systemctl status Jenkins'
                }
            }
            stage('2-processes running on the system-Abisola'){
			steps{
				sh 'ps -ef'
				sh 'sudo systemctl status jenkins'
			}
		}
        
}
}
