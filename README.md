Bug fixes anti-flood

rm -r ~/.telegram-cli/state
___________________________enter
new terminal
___________________________
sudo service redis-server start
___________________________enter
redis-cli
__________________________enter
new terminal
__________________________
cd shatelbot
__________________________enter
./launch.sh
__________________________



# Installation 

```bash
# Tested on Ubuntu 14.04, for other OSs check out https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
```

```bash
# lets install the bot
cd $HOME
git clone https://github.com/amirh0211/shatelbot
cd shatelbot
chmod +x launch.sh
./launch.sh install
./launch.sh # Enter a phone number & confirmation code.

....

