pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "this is build stage"
        echo "$PWD"
        shell('echo this is a build stage.')
        sh '$WORKSPACE/commands.sh'
      }
    }
      
       stage('Test') {
      steps {
        shell ('sh commands.sh')
      }
       }
       
      }
}
