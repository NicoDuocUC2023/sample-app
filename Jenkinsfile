pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Building the Docker image"'
        sh './sample-app.sh'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "Deploying the Docker container"'
        sh 'docker ps -a'
      }
    }
  }
}
