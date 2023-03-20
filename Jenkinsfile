pipeline {
  agent {
    node {
      label 'iQuality'
    }

  }
  stages {
    stage('pom.xml check') {
      steps {
        fileExists 'pom.xml'
      }
    }

  }
}