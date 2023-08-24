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
                 echo 'Deploy'  
                // snDevOpsChange()
	  snDevOpsChange changeRequestDetails: '{ "attributes": {"chg_model": "007c4001c343101035ae3f52c1d3aeb2","assignment_group": "a715cd759f2002002920bde8132e7018" }, "setCloseCode": false }'
	}
      }
	  

  }

	
}





