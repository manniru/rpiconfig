# rpiconfig
Raspberry Configuration and Setup Scripts

sudo apt-get update
sudo apt-get install -y git dialog
mkdir 13131
cd 13131

git clone https://github.com/manniru/rpiconfig.git
cd rpiconfig
chmod +x tightvnc.sh
sudo ./tightvnc.sh
