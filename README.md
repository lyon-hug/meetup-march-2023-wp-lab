# meetup-march-2023-wp-lab

waypoint context create \
  -server-addr=api.hashicorp.cloud:443 \
  -server-auth-token=<AUTH_TOKEN> \
  -server-require-auth=true \
  -server-platform="hcp" \
  -set-default \
  <PROJECT>
  
  
  waypoint context list
