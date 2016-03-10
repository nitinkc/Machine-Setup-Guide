# Ubuntu Server Installation

Use a flash drive to boot through the system.

Use [UNetBootIn](https://launchpad.net/unetbootin/+download) software to make a bootable flash drive. You would need an iso file (installation disk image) for the contents to be shifted into the flash drive.

After installation (pretty intuitive installer), if you like you can install the Desktop. In the beginning, for learning purposes, the desktop is advisable.

`sudo apt install --without-recommends ubuntu-desktop`

restart using cntl+alt+delete from command line mode.

check the ip address to be given to the students (ifconfig)

Login to the server from its network (synergy is the user name)
`ssh synergy@10.1.10.229`

To copy a file from the Desktop of the Server to the current working directory (.) of the host machine, issue the following command
`scp synergy@10.1.10.229:~/Desktop/nitin.txt .`
