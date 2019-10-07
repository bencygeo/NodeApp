node {

  checkout scm
  def dockerImage

  stage('Build image') {
    dockerImage = /usr/local/bin/docker.build("dockerben123/docker-test:latest")
  }

  stage('Push image') {
    dockerImage.push()
  }   

}
