node{
 stage 'Checkout'
 git poll: true, url: 'git@github.com:ReDeploy-IO/template.git', credentialsId: '97290e0f-0e1c-4afe-b238-5a3c90771816'

 stage 'Build'
 sh "docker-compose up"
}
