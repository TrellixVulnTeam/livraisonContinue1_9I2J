pipeline {
	agent any
	stages{

		stage('clone and clean repo'){
			steps {
				cleanWs()
				sh "git clone -b master https://github.com/feridromdhane/livraisonContinue.git"
			}
		}

		

	}
}
