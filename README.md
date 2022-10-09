# linux_backup
<h1> Linux BackUp\Installation manual </h1>

<h3># Linux first configuration </h3>

https://demirrovv.wordpress.com/2014/03/31/soundset/ - volume settings<br>
pulseaudio 
aptitude install alsa-oss alsa-tools alsa-utils 

/etc/default/keyboard - "us,ru" : "grp:alt_shift_toggle" - russian lang installation<br>
https://losst.ru/ustanovka-drajvera-nvidia-v-debian-10 - nvidia driver install<br>

sudo apt install nvidia-driver linux-image-amd64
sudo apt install linux-headers-amd64

https://habr.com/ru/post/515750/ - i3 i3gaps config<br>

<h3># i3 gaps installation #</h3>

git clone https://github.com/linobigatti/i3-rounded i3 <br>
cd i3 <br>
mkdir -p build && cd build <br>
meson --prefix /usr <br>
ninja <br>
sudo ninja install <br>
