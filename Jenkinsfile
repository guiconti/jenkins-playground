pipeline {
  agent any

  parameters {
    booleanParam(defaultValue: true, description: 'User flag?', name: 'userFlag')
  } 


  stages {
    stage("foo") {
      steps {
        script {
          sh "./example.sh ${userFlag}"
        }
        echo "test: ${params.userFlag}"
      }
    }
  }
}