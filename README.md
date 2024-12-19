# Pi5 Update And dist-upgrade
sudo apt-get update
sudo apt-get dist-upgrade

# แก้ปัญหา NodeJs Version
# Pi Install Version  NodeJs v22.12.0
wget https://nodejs.org/dist/v22.12.0/node-v22.12.0-linux-arm64.tar.xz

tar -xvf node-v22.12.0-linux-arm64.tar.xz

cd node-v22.12.0-linux-arm64

rm -f -f node-v22.12.0-linux-arm64.tar.xz

sudo cp -R * /usr/local/

cd ../

rm -r -f node-v22.12.0-linux-arm64

# install SocketIO
npm install socket.io --save

node index.js

http://[RaspberryPi_IP]:8080/
