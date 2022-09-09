# ansible-opensips

export PATH=$PATH:/usr/local/sbin
echo "export PATH=$PATH:/usr/local/sbin" > /root/.bashrc
apt install git python-pip -y
pip install ansible 
ssh-keygen -t rsa -b 4096
git clone https://github.com/nasosu/ansible-opensips.git
mkdir /etc/ansible
mkdir /root/.ansible
mkdir /root/.ansible/roles
cp -r ansible-opensips/roles /root/.ansible
