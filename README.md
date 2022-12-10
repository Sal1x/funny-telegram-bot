## Setup
`pip3 install -r requirements.txt`  
`mv _secrets.template _secrets`  
Update secrets with your data  

Setup redis
https://redis.io/docs/getting-started/installation/install-redis-on-linux/  
https://realpython.com/python-redis/  

## Run
Start redis
`sudo redis-server /etc/redis/6379.conf`  
  
Requires python 3.7+
`python3 main.py`