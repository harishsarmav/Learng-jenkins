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
            env.abc = "Hello"
            def xyz = 10

            print "abc = ${abc}"
            print "xyz = ${xyz}"

            print abc

          }

          script {
            print "abc = ${abc}"
          }
        }
      }

      stage('Test1') {
        steps {
          script {
            print "abc = ${abc}"
          }
        }
      }
            
    }
}