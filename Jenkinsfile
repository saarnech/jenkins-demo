pipeline {
  agent any
  stages {
    stage('Run hello.sh') {
      steps {
        sh 'ls -la'             // show files for debugging
        sh 'chmod +x hello.sh'  // safe even if already executable
        sh './hello.sh'
      }
    }
  }
}
