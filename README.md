# flasking
## Creating base flask server

To create the base server:
```
cd app
python main.py
```

## Creating base server using docker

First build the container:
```
docker build -t flasking_it .
```

Then run the container binding the correct port:
```
docker run -p 1111:1111 flasking_it
```

To leave it running detached on the background:
```
docker run -p 1111:1111 -d flasking_it 
```
