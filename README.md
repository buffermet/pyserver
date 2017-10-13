# :warning: NO DOWNLOAD REQUIRED

## 📃 Installation

```
sudo echo -e "python -c 'import socket; print \"\033[92mhttp://\" + str( socket.gethostbyname(socket.gethostname() ) ) + \":8000\033[0;0m\";'; python -m SimpleHTTPServer;" > /usr/bin/pyserver
sudo chmod +x /usr/bin/pyserver
```

## Deployment

```
sudo pyserver
```

![screenshot from 2017-10-13 18-58-47](https://user-images.githubusercontent.com/29265684/31538338-959c3778-b048-11e7-8c57-17db9fdccad3.png)
