pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/learnwithvikasjha/demo', poll: true)
      }
    }
      
       stage('Test') {
      steps {
        shell ('echo "This is a test stage."')
      }
       }
       
      }
}
