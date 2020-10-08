pipeline {
  agent any
  stages {
    stage('build') {
      steps{
     sh'git branch: '13.0', credentialsId: 'github credentials', url: 'https://github.com/vpolice3/openeducat_erp.git''
      }
    }
  }
}
