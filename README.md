# :warning: NO DOWNLOAD REQUIRED

## Installation

```
sudo echo -e "python -c 'import socket; print \"\033[92mhttp://\" + str( socket.gethostbyname(socket.gethostname() ) ) + \":8000\033[0;0m\";'; python -m SimpleHTTPServer;" > /usr/bin/pyserver
sudo chmod +x /usr/bin/pyserver
```

## Deployment

```
sudo pyserver
```
