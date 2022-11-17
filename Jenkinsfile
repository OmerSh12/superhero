pipeline{
  agent any
  stages{
    stage('test'){
      steps{
        script{
          sh(script: "ls -ltr", returnStdout: true)
        }
      }
    }
  }
}
