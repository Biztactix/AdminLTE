cd /var/www/html/admin
sudo git remote rm origin
sudo git remote add origin https://github.com/Biztactix/AdminLTE.git
sudo git config master.remote origin
sudo git config master.merge master
sudo git fetch origin
sudo git checkout Biztactix-Changes