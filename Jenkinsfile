pipeline {
  agent {label 'node-01'}
  environment {
    HARBOR = credentials('harbor-account')
  }
  stages {
    stage('env') {
      steps {
        sh 'env > text.txt'
      }
    }
  }
}
