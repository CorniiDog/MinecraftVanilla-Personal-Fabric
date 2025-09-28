# Installation:

1. Run command to install screen: `which screen || sudo apt-get update && sudo apt-get install -y screen`

# Instructions:

1. To connect to screen session: `screen -r mc`

2. To disconnect from screen session: `Ctrl+A` then `D`


ALTERNATIVELY, you can configure rcon in server.properties:
```
rcon.password=yourpassword
rcon.port=25575
```

Install `mcrcon` via:

```
git clone https://github.com/Tiiffi/mcrcon.git
cd mcrcon
make
sudo make install
```

Then run minecraft command via:

`mcrcon -H 0.0.0.0 -P 25575 -p whoop "say Testing"`