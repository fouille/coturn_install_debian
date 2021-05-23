# coturn_install_debian
Auto Install Coturn (STUN &amp; TURN) for Debian 10 Buster

# Install
Must be run in root.
```
apt install wget -y && wget -O- https://raw.githubusercontent.com/fouille/coturn_install_debian/main/install.sh | bash
```
#Argument's install 
You can add arguments with your installation
```
wget https://raw.githubusercontent.com/fouille/coturn_install_debian/main/install.sh
chmod +x install.sh
./install.sh #no argument classic installation
./install.sh -r #remove Coturn and Certbot
./install.sh -d #Configure TURN (STUN must be already configured)
``` 
