# crostini-ansible

I have to powerwash my Chromebook a lot. And I get new chromebooks regularly, this is a quick way to rebuild my Crostini VM. Download `crostini.yaml` to your Linux Files director and run the following two commands.

```
sudo apt-get install ansible
sudo ansible-playbook crostini.yaml
```
