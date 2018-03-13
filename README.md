# :warning: NO DOWNLOAD REQUIRED

## 📃 Installation

```
sudo echo -e "if [ $# -eq 0 ]; then PORT=8000; else PORT=$1; fi; python -c 'import socket; print "^[[92mhttp://" + str( socket.gethostbyname(socket.gethostname() ) ) + ":'$PORT'^[[0;0m";'; python -m SimpleHTTPServer $PORT;" > /usr/bin/pyserver
sudo chmod +x /usr/bin/pyserver
```

## Deployment

```
sudo pyserver 8000
```

![screenshot from 2017-10-13 18-58-47](https://user-images.githubusercontent.com/29265684/31538338-959c3778-b048-11e7-8c57-17db9fdccad3.png)
