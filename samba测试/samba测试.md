  213  sudo apt install samba
  214  mkdir data
  215  ll
  216  sudo useradd share
  217  cat /etc/passwd
  218  ll
  219  chmod 755 data
  220  ll
  221  sudo chown share:share data
  222  ll
  223  sudo mv data /
  225  sudo gedit /etc/samba/smb.conf
  226  sudo smbpasswd -a share
  227  sudo systemctl restart smbd.service
  228  ls /data
  229  sudo mv data /
  230  ll /
  251  sudo gedit /etc/samba/smb.conf
  252  sudo systemctl restart smbd.service
  253  sudo systemctl status smbd.service
  254  cd
  255  Downloads
  256  sudo cp ../Downloads/wps-office_11.1.0.11664_amd64.deb /data