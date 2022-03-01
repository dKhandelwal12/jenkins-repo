pipeline {
  agent any 
  stages {
    stage('Build') { 
      steps {
          // 
      }
    }
    stage('Test') { 
      steps {
          // 
      }
    }
    stage('Deploy') { 
      steps {
          // 
      }
    }
  }
  post {
  
    always {
      emailext body: "Summary", subject: "Pipeline", to: "deepak.khandelwal@zupee.in"
    }
  }
}
