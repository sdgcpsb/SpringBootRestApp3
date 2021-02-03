pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'I am in Build'
      }
    }

    stage('') {
      steps {
        javadoc(javadocDir: 'target/api-docs/', keepAll: true)
      }
    }

  }
}