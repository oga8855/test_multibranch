pipeline {
  agent {
    label 'linux'
  }
  
  stages {
    stage ('Script') {
      steps {
        sh 'chmod +x ./ilki.sh'
        sh './ilki.sh'
      }
    }
  }
}
