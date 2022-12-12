# reverse_proxy

## Installation and Use

First of all, this project use two sample html files but you can use it for your own services through editing dockerfiles, docker-compose.yml and allocating whatever you want in folders "site1/" and "site2/".

Once docker is already installed and running, the only thing you have to do is to execute the next command in the main directory:
```bash
docker-compose up
```

Now all services should be up and running and you may be able to acces both sites in localhost/site1 and localhost/site2.

## Configure Proxy

The file Default.conf will be allocated in a mounted volume so you only have to open it from your project and make the proper changes.