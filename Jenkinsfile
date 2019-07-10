node {
  stage("Git Checkout"){
    checkout(scm)
  }
  stage ("Run Python"){
    sh '/usr/local/bin/python hello-world.py'
  }
}
