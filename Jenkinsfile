pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build complate successful'
        timeout(time: 4, unit: 'SECONDS') {
          sh 'sleep 10'
        }
      }
    }
    stage('Test') {
      steps {
        echo 'testing complate successful'
      }
    }
      stage('Deploy') {
      steps {
        echo 'Deploy complate successful'
      }
    }  
  }
}