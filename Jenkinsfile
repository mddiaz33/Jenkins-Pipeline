pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'echo "This is $BUILD_Number of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}