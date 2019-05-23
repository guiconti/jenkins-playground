pipeline {
  agent any

  stages {
    stage("foo") {
      steps {
        script {
          sh "./example.sh true"
        }
        echo "test: true"
      }
    }
  }
}
