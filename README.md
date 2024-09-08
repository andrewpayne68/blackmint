![image-1](https://github.com/andrewpayne68/blackmint/blob/e82ed3194802f0282509b70e612ace1faa20fdd9/BLACKMINT%20logo.png)

This is a fully Darkest Green GTK Flat Remix with Bloom Green icon themed installation build script to convert Linux Mint 22 LTS installation to BLACKMINT. It is recommended to execute on a clean installation.  

Download the latest Ubuntu ISO from here: ` https://www.linuxmint.com/download.php `

_Check this repo for one for Ubuntu 24.04 - https://github.com/andrewpayne68/blackbuntu2404_

If you have issues with VMWare Workstation Pro 17.6 then I would recommend updating the GPU Drivers using this repo: ` https://gist.github.com/andrewpayne68/ba97ad0ec93fed9c0631ad66de858841 `

Installation Script
-

```
sudo apt-get -y install git
```
```
git clone https://github.com/andrewpayne68/blackmint.git
```
```
cd blackmint
```
```
tar -xf BLACKMINT.tar.xz
```
```
cd BLACKMINT &&./build.sh
```

OR run the all-in-one bash command
```
sudo apt-get -y install git && git clone https://github.com/andrewpayne68/blackmint.git && cd blackmint && tar -xf BLACKMINT.tar.xz && cd BLACKMINT && ./build.sh
```
\
\
After the first reboot, run Nala to update Blackbuntu
-
```
sudo nala update && sudo nala upgrade -y
```

\
\
Screenshot
-
![image-1](https://github.com/andrewpayne68/blackmint/blob/7ce03e40c40db0c283cb6a8a131e9e0cbefcd554/Screenshot%202024-09-08.png)





