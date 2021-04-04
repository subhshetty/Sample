pipeline {
   agent any

   stages {
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