@Library('github.com/vdavityan/demo-shared-pipeline') _

pipeline {
   agent any

   stages {
      stage('Call Library Function with an arguement') {
         steps {
            script {
               helloArgs('Jenkins')
            }
         }
      }
      stage('Call additional Library Functions') {
         steps {
            script {
               helloArgs.goodbyeWorld('Jenkins')
            }
         }
      }
   }
}