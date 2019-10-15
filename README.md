# crostini-ansible

I have to powerwash my Chromebook a lot. And I get new chromebooks regularly, this is a quick way to rebuild my Crostini VM. Download `crostini.yaml` to your Linux Files director and run the following two commands.

```
sudo apt-get install ansible
sudo ansible-playbook crostini.yaml
```

# Configuring Terminal

You can configure the the look of the CrOS terminal app by pressing CTRL+SHIFT+P. I've added powerline compatible fonts by changing the following settings:
* **Custom CSS URL** to `https://cdn.jsdelivr.net/gh/wernight/powerline-web-fonts@ba4426cb0c0b05eb6cb342c7719776a41e1f2114/PowerlineFonts.css`
* **Text Font Family** to `Hack, monospace`
* **Text Font Size** to `14`

# Screenshot

![Crostini Screenshot showing powerline, tmux, htop, and vim](https://i.imgur.com/0K2sSOQ.png)
