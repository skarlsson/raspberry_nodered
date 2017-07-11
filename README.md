# README #

```
sudo apt-get install ssh ansible git

git config --global user.email "your@email"
git config --global user.name "your name"

git clone https://github.com/skarlsson/raspberry_nodered.git
cd raspberry_nodered

#### common stuff
ansible-playbook -i "localhost," -c local common.yml


#### common stuff
ansible-playbook -i "localhost," -c local mosquitto.yml


