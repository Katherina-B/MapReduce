## Hadoop MapReduce
## Requirements
 * [Docker 20+](https://www.docker.com/get-started)
 * [Data](https://www.kaggle.com/usdot/flight-delays?select=flights.csv) - save in directory data
 ## Bootstraping your environment
```bash
$docker-compose up -d
$./run.sh
$docker exec -t apache-hadoop-namenode-1 chmod u+x /my_volume/main.py
```
##Run
```bash
$docker exec -t apache-hadoop-namenode-1 python3 /my_volume/main.py -r hadoop hdfs:///flights.csv
