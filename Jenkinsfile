def abc="test"

pipeline {
  agent any
  options{
    timestamps()
  }
  stages {
    stage("Custom") {
      steps {
        script {
          sh "echo This is test Jenkinsfile"
          sh "abc value is $abc"
        }
      }
    }
  }
  
}
