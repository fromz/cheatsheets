# Docker
## Acting per label
* docker stop $(docker ps -a --filter "label=org.label-schema.group=kafka" -q)
* docker rm $(docker ps -a --filter "label=org.label-schema.group=kafka" -q)
