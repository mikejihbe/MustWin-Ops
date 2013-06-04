customhogs
==========

# RAILS SERVER SETUP
sudo apt-get install build-essential nginx  git-core libreadline6-dev zlib1g-dev libssl-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev autoconf libgdbm-dev libncurses5-dev automake libtool bison pkg-config libffi-dev
sudo apt-get install postgresql-9.1
sudo apt-get install imagemagick mongodb-server 
curl -L https://get.rvm.io | sudo bash -s stable
sudo usermod -aG rvm ubuntu
rvm install ruby-1.9.3-p286
sudo mkdir -P /www/customhogs/releases /www/customhogs/shared/logs
sudo chown -R ubuntu:ubuntu /www/customhogs


# Dev Server Setup

install mongodb
install imagemagick



