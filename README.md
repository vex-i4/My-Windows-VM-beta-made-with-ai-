Text me on discord at: Enko_WZ
If something goes wrong!
This creates your Ubuntu screen. Paste this first:
if the desktop start command says
Error response from Daemon manifest unkown run:

docker run -d --name=webtop -p 3000:3000 linuxserver/webtop:latest

Bash
docker run -d --name=webtop -p 3000:3000 ghcr.io/linuxserver/webtop:ubuntu-xfce-jammy
desktop!)

🛠️ STEP 2: Prepare for Steam

Inside the Desktop terminal (the one on port 3000), paste these to set everything up:

Enable 32-bit: sudo dpkg --add-architecture i386 && sudo apt update
Add the App Store: sudo add-apt-repository universe && sudo apt update
STEP 3: Install Steam

Now, run the actual installation:
sudo apt install steam -y
IF IT FAILS (Emergency Fixes)

If the step above didn't work, use these "Force" commands:
Fix broken files
sudo apt-get install -f -y
Download Steam directly:
wget https://repo.steampowered.com/steam/archive/precise/steam_latest.deb && sudo apt install ./steam_latest.deb -y

Open Steam
To make the Steam window pop up on your screen:
steam -vgui &
