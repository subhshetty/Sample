pipeline {
   agent any

   stages {
      stage('Checkout') {
         steps {
            git credentialsId: '94b69472-cb9e-4160-8a01-a39551927876', url: 'https://github.com/subhshetty/Sample.git'
         }
      }
      stage('Install') {
         steps {
            bat label: '', script: 'python hello.py'
         }
      }
      stage('Test') {
         steps {
             echo "the code ran successfully"
         }
      }
   }
}