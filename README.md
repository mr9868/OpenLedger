# OpenLedger Auto installer
testnet.openledger.xyz
> [!IMPORTANT]
> First of all, you must install VNC on your server. You can follow this [guide](https://github.com/mr9868/Vnc)
> After VNC installed on your server, you must download VNC viewer on your monitoring device. You can download from [this](https://www.realvnc.com/en/connect/download/viewer)
> After that, You must connected to your VNC server. to connect you must put example : `IPaddres:5901` to connect to the VNC server
> And then open your VNC server and execute this :
> ```
> wget -O openLedger.zip https://cdn.openledger.xyz/openledger-node-1.0.0-linux.zip ;
> unzip openLedger.zip ;
> rm -rf openLedger.zip ;
> dpkg -i openledger* ;
> openledger-node --no-sandbox;
> ```
> The popups app will be show, and you can go with next step until you can connect your node
> Alright, you did it !

