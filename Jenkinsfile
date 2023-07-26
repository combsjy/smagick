pipeline {

	agent none

  stages {

  	stage('Maven Install') {

    	agent {

      	docker {

        	image 'alpine:latest'

        }

      }

      steps {

      	sh 'echo woot && ls -al'

      }

    }

  }

}
