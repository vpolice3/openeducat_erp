timeout(time:60, unit:'MINUTES'){
  node{
    stage('Checkout'){
      sh 'git branch: '13.0', credentialsId: 'github credentials', url: 'https://github.com/vpolice3/openeducat_erp.git''
    }
  }
}
