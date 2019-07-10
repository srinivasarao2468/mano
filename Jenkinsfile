node {
  stage("Git Checkout"){
    checkout(scm)
  }
  stage ("Run Python"){
    sh 'python hello-world.py'
  }
}
