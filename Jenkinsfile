pipeline {
  agent any

  parameters {
    string(defaultValue: "TEST", description: 'Teste?', name: 'userTest')
    choice(choices: ['US-EAST-1', 'US-WEST-2'], description: 'What test?', name: 'region')
  } 


  stages {
    stage("foo") {
      steps {
        echo "test: ${params.region}"
      }
    }
  }
}