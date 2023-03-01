# meetup-march-2023-wp-lab

waypoint context create \
  -server-addr=api.hashicorp.cloud:443 \
  -server-auth-token=<AUTH_TOKEN> \
  -server-require-auth=true \
  -server-platform="hcp" \
  -set-default \
  <PROJECT>
  
  
  waypoint context list
  
  
  waypoint runner install \
  -platform=kubernetes \
  -server-addr=api.hashicorp.cloud:443 \
  -k8s-runner-image=hashicorp/waypoint:latest

  
  
  waypoint runner list -plain
  waypoint runner profile list -plain
