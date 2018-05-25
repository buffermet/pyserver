# NO CLONE/DOWNLOAD REQUIRED

## Installation

```
sudo echo -e "if [ $# -eq 0 ]; then PORT=8000; else PORT=$1; fi; python -c 'import socket; print "^[[92mhttp://" + str( socket.gethostbyname( socket.gethostname() ) ) + ":'$PORT'^[[0;0m";'; python -m SimpleHTTPServer $PORT;" > /usr/bin/pyserver
sudo chmod +x /usr/bin/pyserver
```

## Deployment

```
sudo pyserver <port>
```

![pyserver](https://user-images.githubusercontent.com/29265684/37338234-91e4eacc-2702-11e8-96f2-0898252dba92.png)
