pipeline {
  agent any
  stages {
    stage('properties') {
      steps {
        node(label: 'sjc-bld135-lnx') {
          ws(dir: '/') {
            git(url: 'https://cto-github.cisco.com/NFV-BU/SIF.git', branch: 'master', credentialsId: '108c0b80-56ba-4229-8c71-2cf298a4666c')
          }
          
        }
        
      }
    }
  }
}