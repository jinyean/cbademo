pipeline {
  agent any
  stages {
    stage('Get All Rules') {
      steps {
        sh '''curl --location \'https://api.us-west.exabeam.cloud/correlation-rules/v2/rules\' \\
--header \'Authorization: Bearer' 
    }

  }
}
