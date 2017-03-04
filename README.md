# Seahorse Adventures and Funny Boat on RetroPie
Seahorse Adventures and Funny Boat Installer Script for RetroPie
### Installation 

Install the extra scripts

The following clones the repo to your Pi and then the install-scripts.sh installs the scripts in the master branch directly to the proper directories in RetroPie-Setup.

```
git clone https://github.com/moonpi/SeahorseAdventures-FunnyBoat-RetroPie.git
cd RetroPie-Extra/
./install-extras.sh
```
Run the RetroPie Setup Script (seahorse and funnyboat will be in the experimental section)
```
cd
cd RetroPie-Setup
sudo ./retropie_setup.sh
```

This script assumes that you are running it on a Raspberry Pi with the RetroPie-Setup being stored in /home/pi/RetroPie-Setup. If your setup differs, just copy the scripts directly to the folder they need to be in.

Based on zerojay's RetroPie-Extra scripts: https://github.com/zerojay/RetroPie-Extra
