pipeline {
  agent {
    label 'Docker'
  }
  
  stages {
    stage ('Script') {
      steps {
        sh './ilki.sh'
      }
    }
  }
}
