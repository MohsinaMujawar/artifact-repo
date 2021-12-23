pipeline{
  agent any
  stages{
    stage('Archive Artifact'){
      steps{
        archiveArtifacts artifacts: 'output.txt', fingerprint: true
      }
    }
  }
}  
