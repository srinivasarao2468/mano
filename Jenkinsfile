node {
  stage("Git Checkout"){
    checkout(scm)
  }
  stage ("Run Python"){
    sh '/usr/bin/python3 python3 hello-world.py'
  }
}
