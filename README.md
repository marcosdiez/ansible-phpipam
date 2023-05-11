# ansible-phpipam


sudo dnf install --downloadonly  --downloaddir . mariadb-server


sudo dnf install *.rpm --disablerepo=*

sudo dnf install *.rpm --disablerepo=* --skip-broken


sudo dnf install --downloadonly  --downloaddir . mariadb-server
sudo dnf install --downloadonly  --downloaddir . https://dl.fedoraproject.org/pub/epel/epel-release-latest-9.noarch.rpm
sudo dnf install --downloadonly  --downloaddir . mariadb-server
sudo dnf install --downloadonly  --downloaddir . mariadb-server



sudo repotrack --destdir . mariadb-server
sudo repotrack --destdir . https://dl.fedoraproject.org/pub/epel/epel-release-latest-9.noarch.rpm
sudo dnf install -y epel-release-latest-9.noarch.rpm
sudo repotrack --destdir . https://rpms.remirepo.net/enterprise/remi-release-9.rpm
sudo dnf install -y remi-release-9.rpm
sudo dnf module list php
sudo dnf module enable php:remi-7.4

sudo repotrack --destdir . php php-cli php-common net-tools telnet nano python3-PyMySQL.noarch  nginx


du --assumeyes


sudo dnf install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-9.noarch.rpm --assumeyes
sudo dnf install -y https://rpms.remirepo.net/enterprise/remi-release-9.rpm --assumeyes
sudo dnf module list php
sudo dnf module enable php:remi-7.4

sudo dnf install --downloadonly  --downloaddir .  php php-cli php-common net-tools telnet nano python3-PyMySQL.noarch  nginx


# sudo repotrack --destdir . https://rpms.remirepo.net/enterprise/remi-release-9.rpm

# sudo dnf install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-9.noarch.rpm
# sudo dnf install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-9.noarch.rpm

#    18  sudo dnf install -y https://rpms.remirepo.net/enterprise/remi-release-9.rpm
#    19  sudo dnf module list php
#    20  sudo dnf module enable php:remi-7.4
#    21  php -v
#    22  sudo dnf install php php-cli php-common
#    23  php -v
#    24  sudo systemctl stop firewalld