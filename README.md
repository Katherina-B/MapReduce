# Hadoop MapReduce

$ docker-compose up -d

$ ./run.sh

$ docker exec -t apache-hadoop-namenode-1 chmod u+x /my_volume/main.py

#Run

$docker exec -t apache-hadoop-namenode-1 python3 /my_volume/main.py -r hadoop hdfs:///flights.csv

