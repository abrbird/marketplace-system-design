export MY_IP=172.17.0.1
export NETWORK="kafka-net"


up:
	#docker network create ${NETWORK}
	docker-compose -f docker-compose.kafka.yml up --build
up-d:
	#docker network create ${NETWORK}
	docker-compose -f docker-compose.kafka.yml up --build -d
down:
	docker-compose -f docker-compose.kafka.yml down

