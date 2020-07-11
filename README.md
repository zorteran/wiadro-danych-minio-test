# Simple MinIO + Spark test

1. download MovieLens package and unzip it
```
wget http://files.grouplens.org/datasets/movielens/ml-latest.zip
unzip ./ml-latest.zip
```
2. Run
```
sudo docker compose up -d
```
3. At localhost:9001 type MinIO key/secret from docker-compose, create bucket and put files
4. Use docker logs jupyter_container_id/name to open Jupyter in a browser
5. Play with Spark and MinIO


