node {
  stage("Git Checkout"){
    checkout(scm)
  }
  
  stage('Test') {
            sh 'python hello-world.py'
        }
}
