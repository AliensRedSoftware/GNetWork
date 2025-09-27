# desc
* GNetWork - Generate NetWork linux

# effect
* Generate Random Host
* wipe networks
* effect sound notify
* Generate mac_address

# Доп.Конфигурация для роутера нужная если че
0. open default webbrouser
1. open web site - `192.168.0.1 / (RT-GM-2)`
2. login please...
3. enable oneTime DHCP expired 10min devices all
4. applya settings routers
5. success :)

# cfg Конфигурация
* change sound effect -> `~/.config/GNetWork/notify.mp3`
* change resetTimeOut repeat -> `~/.config/GNetWork/resetTimeOut.cfg / (Default 60sec - 1min)`

# install manual (Ubuntu clone debian)
0. please install cmd terminal (Ubuntu clone Deb) -> `sudo dpkg -i GNetWork-deb-{arhiticle}.{arhiticle}` / example `sudo dpkg -i GNetWork-deb-amd64.deb`
1. Use terminal cmd `GNetWork` :)
2. success :)

# build project deb (Ubuntu clone debian)
0. use `git clone https://github.com/AliensRedSoftware/GNetWork-linux`
1. path change please `cd GNetWork-linux/{destribitian}` / example `cd GNetWork-linux/deb`
2. build project deb -> `sudo dpkg-deb --build GNetWork-{arhiticle}` / example `sudo dpkg-deb --build GNetWork-amd64`
3. result file install deb -> `sudo dpkg -i GNetWork-{arhiticle}.deb` / example `sudo dpkg -i GNetWork-amd64.deb`
4. Use terminal cmd GNetWork :)
5. success :)

