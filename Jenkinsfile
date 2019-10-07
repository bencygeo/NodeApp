node {
  stage 'Building image'
  /usr/local/bin/docker.build "mycorp/myapp:${env.BUILD_TAG}"
  //newApp.push() // record this snapshot (optional)
  //stage 'Test image'
  // run some tests on it (see below), then if everything looks good:
 // stage 'Approve image'
 // newApp.push 'latest'
}
