node {
  git '…' // checks out Dockerfile & Makefile
  def myEnv = /usr/local/bin/docker.build 'my-environment:snapshot'
  myEnv.inside {
    sh 'make test'
  }
}
