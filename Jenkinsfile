pipeline {
  agent any
  stages {
    stage('Staging') {
      steps {
        pushToCloudFoundry(organization: 'DawsonDesign', cloudSpace: 'development', credentialsId: 'pdawson2090@gmail.com', target: 'api.run.pivotal.io')
      }
    }
  }
}