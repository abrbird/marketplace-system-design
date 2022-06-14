export MY_IP=172.17.0.1
export NETWORK="kafka-net"


init:
	docker network create ${NETWORK}

up:
	docker-compose -f docker-compose.kafka.yml up --build
up-d:
	docker-compose -f docker-compose.kafka.yml up --build -d
down:
	docker-compose -f docker-compose.kafka.yml down

