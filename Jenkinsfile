pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "Building release ${RELEASE} with log level ${LOG_LEVEL}..."
        }
    }
  }
    environment {
      RELEASE = '20.04'
  }
}
