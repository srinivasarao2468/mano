node {
  stage("Git Checkout"){
    checkout(scm)
  }
  stage ("Run Python"){
    sh '/usr/bin/python hello-world.py'
  }
}
