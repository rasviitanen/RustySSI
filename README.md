### Starting a pool
#### Build the docker file
sudo docker build -f indy-pool.dockerfile -t indy_pool .
#### Start pool of nodes on 127.0.0.1:9701-9708
docker run -itd -p 9701-9708:9701-9708 indy_pool
