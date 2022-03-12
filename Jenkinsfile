def abc="test"

pipeline {
  agent {
    label "master"
  }
  options{
    timestamps()
  }
  stages {
    stage {
      steps {
        script {
          sh "echo This is test Jenkinsfile"
        }
      }
    }
  }
  
}
