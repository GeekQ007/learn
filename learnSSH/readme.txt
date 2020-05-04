#ubuntu18.04
#by zqwang
#install
sudo apt-get install openssh-server
#start or stop
#config default:/etc/ssh/sshd_config, port:22
/etc/init.d/ssh start #start
/etc/init.d/ssh start #stop
/etc/init.d/ssh restart #restart
#login
ssh -p22 username@address


