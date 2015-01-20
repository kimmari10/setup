# setup
# setup ubuntu14.10

sudo apt-get update && sudo apt-get upgrade -y


#git
sudo apt-get install git

#mysql
sudo apt-get install mysql-client mysql-server
sudo apt-get install mysql-workbench

#vim
sudo apt-get install vim

#한영문제
#http://zapary.blogspot.kr/2014/10/ubuntu-1410-ibus-hangul-issue.html

sudo apt-get install ibus-gtk2

#chrome
wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -

sudo sh -c 'echo "deb http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'

sudo apt-get update 

sudo apt-get install google-chrome-stable -y


