node {
  
  def myEnv = /usr/local/bin/docker.build 'my-environment:snapshot'
  myEnv.inside {
    sh 'make test'
  }
}
