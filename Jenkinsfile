def abc="test"

pipeline {
  agent any
  options{
    timestamps()
  }
  stages {
    stage("Checkout") {
      steps {
        script {
          dir("code") {
          sh "echo This is checkout stage"
          checkout scm
          }
        }
      }
    }
  }
  
}
