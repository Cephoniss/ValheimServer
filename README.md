# ValheimServer

## Information for starting server

Navigate to server directory in ~/  
```
cd valheimserver
```
Start Server
```
./start_valheim.sh
```
Update 
```
steamcmd +login anonymous +force_install_dir /path/to/your/Valheim +app_update 896660 validate +exit
```

Update Public Test  
```
steamcmd +login anonymous +force_install_dir /path/to/your/Valheim +app_update 896660 -beta public-test -betapassword "yesimadebackups" validate +exit
```
Worlds directory
```
~/.config/unity3d/IronGate/Valheim/worlds/ 
```
# V Rising Server
## Information for starting server

Navigate to server directory in ~/
```
cd VrisingServer
```

Start Server
```
systemctl start VRising
```
Server Status
```
systemctl status VRising
```
Update
```
steamcmd +login anonymous +force_install_dir /home/steam/VrisingServer +app_update 1829350 +quit


