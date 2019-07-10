node {
  stage("Git Checkout"){
    checkout(scm)
  }
  docker.image('python:3.5.1').inside {
        stage('Test') {
            sh 'python hello-world.py'
        }
    }
}
