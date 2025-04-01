# qtile_config
Qtile linux config for laptop (Dell) with Rhino distro and EndeavourOS

### For Wlan need to execute command
```python
pip install iwlib psutils
```

If you are getting error while installation iwlib please install library *libiw-dev*
for Rhino:
```bash
sudo apt install libiw-dev
```

Nerd Font family installation: [Link](https://github.com/ryanoasis/nerd-fonts)

Qtile installation guide you can find on official [site](https://docs.qtile.org/en/latest/manual/install/index.html) 

[Config file](https://github.com/Alex2182/qtile_config/blob/main/config.py) place into folder ~/.config/qtile/

There are several ways to start Qtile. The most common way is via an entry in your X session manager's menu. The default Qtile behavior can be invoked by creating a [qtile.desktop](https://github.com/qtile/qtile/blob/master/resources/qtile.desktop) file in /usr/share/xsessions.
