===
Crunchie
===

That's an example live-build environment, using CrunchBang Linux\Debian as a base system with some tweaks
for better end-user experience.

===
Building
===
1. Install apt-cacher-ng:
    sudo apt-get install apt-cacher-ng
or comment line
    --apt-http-proxy=http://localhost:3142 --apt-ftp-proxy=ftp://localhost:3142
in auto/config.

2. Install live-build suite:
    sudo apt-get install live-build
Tested on l-b v.3.0.5 (Debian Wheezy), use 4.x on your own risk.

3. Customize configs if neccessary.

4. Start building!
    lb config
    sudo lb build

===
Known issues
===
dpkg fails on tint2 package when installing user lists - restart the building and it should work.

===
Used software
===
Debian

CrunchBang Linux and everything in it

OpenSnap (https://github.com/lawl/opensnap)

f.lux (https://justgetflux.com/linux.html) - uncomment the line in .config/openbox/autostart and replace example coordinates with yours

oh-my-zsh (https://github.com/robbyrussell/oh-my-zsh) - awesome tweaks for awesome shell!

===
Included themes
===
SlimOne OpenBox theme: http://box-look.org/content/show.php/SlimOne?content=76101

Evolvere icons: http://xfce-look.org/content/show.php/Evolvere+Icon+theme?content=164368
