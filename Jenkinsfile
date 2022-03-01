pipeline {
  agent any 
  stages {
    stage('Build') { 
      steps {
          echo "Build app"
      }
    }
    stage('Test') { 
      steps {
          echo "Test app"
      }
    }
    stage('Deploy') { 
      steps {
          echo "Deploy app"
      }
    }
  }
  post {
  
    always {
      emailext body: 'Pipeline script from SCM Summary', subject: 'Pipeline Status', to: 'deepak.khandelwal@zupee.in'
    }
  }
}
