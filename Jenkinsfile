pipeline {
  agent any
  stages {
    stage('Stage1') {
      parallel {
        stage('Stage1') {
          steps {
            sh 'echo "This is $BUILD_Number of demo $DEMO"'
          }
        }

        stage('') {
          steps {
            sh 'echo "This is $BUILD_NUMBER of DEMO $DEMO"'
          }
        }

      }
    }

  }
  environment {
    DEMO = '1'
  }
}