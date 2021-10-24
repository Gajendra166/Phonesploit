pkg up -y

pkg install git -y

pkg install python -y

pkg install openssl-tool

pkg install wget -y

pip install colorama

git clone https://github.com/MasterDevX/Termux-ADB
cd Termux-ADB

chmod +x InstallTools.sh

bash InstallTools.sh

cd 

git clone https://github.com/01010000-kumar/PhoneSploit

cd PhoneSploit

python phonesploit.py

y
