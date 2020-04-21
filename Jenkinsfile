node {
  stage ('GIT Repository Checkout') {
    git 'https://github.com/sonyvimal/my-app.git'
  }
  stage ('Compile the package') {
    sh 'mvn package'
  }
}

