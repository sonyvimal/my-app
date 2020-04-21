node {
  stage ('GIT Repository Checkout') {
    git 'https://github.com/sonyvimal/my-app.git'
  }
  stage ('Compile the package') {
    sh 'mvn package'
  }
  stage ('Email Notification'){
  mail bcc: '',
  body: 'Welcome to Jenkins Email Alerts', cc: '', from: '', replyTo: '',
  subject: 'MAIL | JENKINS SERVER', to: 'sony.vimal@gmail.com'
  }
}

