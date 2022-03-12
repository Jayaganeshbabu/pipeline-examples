def abc="test"

pipeline {
  agent {
    label "master"
  }
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
