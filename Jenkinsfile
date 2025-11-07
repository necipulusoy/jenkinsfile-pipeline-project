pipeline {
  agent {
    kubernetes {
      label 'k8s-agent-multi'
      defaultContainer 'maven'
    }
  }

  stages {
    stage('build') {
      steps {
        echo "Reinvent Yourself"
        sh 'echo second step'
        sh 'echo another step'
        sh '''
          echo 'Multiline'
          echo 'Example'
        '''
        echo 'not using shell'
      }
    }

    stage('test') {
      steps {
        echo "Reinvent Yourself"
        sh 'echo second step'
        sh 'echo another step'
        sh '''
          echo 'Multiline'
          echo 'Example'
        '''
        echo 'not using shell'
      }
    }

    stage('last') {
      steps {
        echo "Reinvent Yourself"
        sh 'echo second step'
        sh 'echo another step'
        sh '''
          echo 'Multiline'
          echo 'Example'
        '''
        echo 'not using shell'
      }
    }
  }
}
