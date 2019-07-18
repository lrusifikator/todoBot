# todoBot


Overview
========

It is a telegram chat task manager. 
Basically i wrote it to practice a bit in python and telegram API. If someone need the code you can just take any part you want, I'm totally fine with it :)

Installation
============

Required: python3, pip3, setuptools, config

```bash
clone https://github.com/lrusifikator/todoBot
cd todoBot
sudo apt install python3 python3-pip
pip3 install --pre --upgrade -r requires.txt
sudo python3 setup.py install
```
Or just: `sudo pip install todoBot`

Usage
=====

It is possible to use it only if you have a free server where you can
run it consistently. It doesn't need much; a low-end PC would be more
than enough.

Creating a bot
--------------

1.  Search for the “botfather” telegram bot in the telegram search bar
    (it is the one that’ll assist you with creating and managing your
    bot)
2.  Click on or type `/newbot` to create a new bot.

Setting up the todoBot
------------------------

3.  Botfather will send you a bot token. Copy it
4.  Type in the terminal `set-todoBot` and insert the token
5.  Type in the terminal `todoBot`

If you want it to run on a server using ssh, type in the ssh session:
`nohup todoBot &> /dev/null &` It will keep the bot
running after leaving the ssh session, delete all the output and hide the
process.

Contact information
===================

<yakushev.rusl101@gmail.com>
