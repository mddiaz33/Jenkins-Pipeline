pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      environment {
      LOG_LEVEL='INFO'
      }
      steps {
        echo "Building release ${RELEASE} with log level ${LOG_LEVEL}..."
        }
    }
      stage('Test') {
      steps {
        echo "Building release ${RELEASE} with log level ${LOG_LEVEL}..."
        }
    }
  }
    environment {
      RELEASE = '20.04'
  }
}
