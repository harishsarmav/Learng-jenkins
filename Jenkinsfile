pipeline {

  agent {
    label ' ansible '
  }

  stages {

    stage('Hello') {
      steps {
        echo 'Hello World'
        mail bcc: '', body: '''Dear Harish,
        I am writing to express my interest in the DevOps Entry Level Position Amazon. I am a Mechanical Engineer with over 5 years of experience in the field, and I am eager to transition my career into the world of DevOps.

        I have a strong understanding of mechanical systems, and I am well-versed in project management and problem-solving. I have always been fascinated by technology and automation, and I have been keeping myself up to date with the latest developments in the field of DevOps.

        I am confident that my experience in mechanical engineering and my interest in technology and automation make me an excellent candidate for the position. I am excited about the opportunity to work with your team and contribute to the growth and success of Amazon.

        I am excited about the opportunity to join Amazon and am confident that I will be a valuable addition to your team. I would appreciate the opportunity to discuss my qualifications further. Thank you for considering my application.

        Sincerely,
        Harish Sarma V''', cc: 'harishsarma.velavalapalli@gmail.com', from: '', replyTo: '', subject: 'Hello Harish', to: 'harishsarma.v@gmail.com'
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