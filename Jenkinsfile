pipeline {
  agent any
  stages {
       stage('Build') {
           steps {
              echo 'build'

           }
       }
       stage('Test') {
           steps {
              echo 'Test'
           }
       }
      stage('Deploy') {
           steps {
                   
              snDevOpsChange changeRequestDetails: '{ "attributes": { "short_description": "pkgName => ${pkgName}", "description": "changeRequestId => ${changeRequestId}"}}'
	  
	}
      }

  }

}
