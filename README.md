##### Debug with containers
###### # `docker-compose -f single-peer-ca.yaml up`
#### Start the container
###### # `docker-compose -f single-peer-ca.yaml start`
#### Stop the container
###### # `docker-compose -f single-peer-ca.yaml stop`
#### Stop all containers
###### # `docker stop $(docker ps -a -q)`
#### Remove all images except main images:
###### # `docker rmi -f $(docker images | grep -v 'hyperledger\|sofocle'| awk {'print $3'})`
