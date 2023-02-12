// pipeline {
//
//   agent {
//     label ' ansible '
//   }
//
//   stages {
//
//     stage('Hello') {
//       steps {
//         echo 'Hello World'
//       }
//     }
//   }
//   post {
//     always {
//       echo " Sending email"
//     }
//
//     changed {
//       echo " Blah Blah Blah "
//
//     }
//   }
//
// }

@Library('roboshop') _

pipeline {
    agent any
    stages {
      stage('Test') {
        steps {
          script {
            test()
          }
          
        }
      }
    }
}