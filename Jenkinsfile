def abc="test"

pipeline {
  agent any
  options{
    timestamps()
  }
  stages {
    stage("Test") {
      steps {
        script {
          sh "echo This is test Jenkinsfile"
        }
      }
    }
  }
  
}
