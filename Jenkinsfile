pipeline {
  agent {
    label 'docker'
  }
  
  stages {
    stage ('Script') {
      steps {
        sh './ilki.sh'
      }
    }
  }
}
