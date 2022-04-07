 pipeline {
     triggers {
        pollSCM('') // Enabling being build on Push
     }
     agent any

     stages {

         stage("build"){
             steps {
                 echo 'building app'
             }
         }
         stage("test") {
             steps{
                 echo 'testing appa2'
             }
         }
         stage("deploy") {
             steps{
                 echo 'deploying app2ss'
             }
         }
     }
     
 }