setfont iso01-12x22.psfu.gz or setfont ter-132b

iwctl #command to check network
device list #check devices
station list #check stations
station wlan0 connect 'Wifi_name'
exit

get ip address
ip addr

check sshd
sudo systemctl start sshd

then set a pass for the system
passwd

time to make the partitions
check the drives by using
lsblk

for security but this takes long do this
dd if=/dev/urandom of=/dev/'diskname' bs=4096 status=progress

timedatectl set-ntp true #This is going into curl mode
