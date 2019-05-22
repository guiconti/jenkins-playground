pipeline {
  agent any

  parameters {
    booleanParam(defaultValue: true, description: 'User flag?', name: 'userFlag')
  } 


  stages {
    stage("foo") {
      steps {
        echo "test: ${params.userFlag}"
      }
    }
  }
}