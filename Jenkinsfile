node{
 stage 'Checkout'
 git poll: true, url: 'git@github.com:ReDeploy-IO/docker-compose-lamp.git', credentialsId: '98aa581c-a54c-44f1-a3da-af49d64567f3'

 stage 'Build'
 sh "docker-compose up"
}
