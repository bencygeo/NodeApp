node {

  checkout scm
  

  stage('Build image') {
    dockerImage = /usr/local/bin/docker.build("dockerben123/docker-test:latest")
  }

  stage('Push image') {
    dockerImage.push()
  }   

}
