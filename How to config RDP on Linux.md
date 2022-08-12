The purpose here is to connect with RDP with a Windows Machine to a Linux Machine

### On Linux Machine
Install xrdp :
`sudo apt install xrdp`

Start service :
`sudo /etc/init.d/xrdp start`

Check status :
`sudo /etc/init.d/xrdp status`

Get the IP address :
`Ìfconfig`

### Windows machine
- Search for "RDP" in the Windows searchbar
- Enter the Linux machine IP address
- Enter the credentials
- Warning, the user must not be connected to the Linux machine
