pipeline {

  agent {
    label ' ansible '
  }

  stages {

    stage('Hello') {
      steps {
        echo 'Hello World'
      }
    }
  }
  post {
    always {
      echo " Sending email"
    }

    changed {
      echo " Blah Blah Blah "

    }
  }

}