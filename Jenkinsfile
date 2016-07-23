node{
 stage 'Checkout'
 git poll: true, url: 'https://github.com/ReDeploy-IO/docker-compose-lamp.git'

 stage 'Build'
 sh "docker-compose up"
}
