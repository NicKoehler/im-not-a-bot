.. image:: https://github.com/NicKoehler/im-not-a-bot/blob/master/images/logo.png?raw=true
   :align: center
   :alt: im-not-a-bot Logo
===============
Sections
===============

- `Introduction`_

- `Installing`_

- `Configure`_

- `Starting`_

============
Introduction
============
I'm a python beginner, so please don't be mad at my code 😂


I'M SORRY FOR MY ENGLISH ON THIS PROJECT, **I'M ITALIAN** AND I CAN'T WRITE ENGLISH PERFECTLY.
IF YOU FIND TYPOS, OR ANYTHING ELSE YOU CAN `CONTACT ME <https://t.me/nickoehler>`_.

This bot it's just a simple implementation of
a captcha for everyone that joins a telegram group.

Tested only with python 3.7

.. image:: https://github.com/NicKoehler/im-not-a-bot/blob/master/images/screen.png?raw=true
   :align: center
   :alt: im-not-a-bot Logo

============
Installing
============

Install im-not-a-bot cloning this repo:

.. code:: shell

    $ git clone https://github.com/NicKoehler/im-not-a-bot

Then install the requirements:

.. code:: shell

    $ cd im-not-a-bot
    $ pip install -r requirements.txt

============
Configure
============

the first thing you need to do it's **create a telegram bot** using the `BotFather <https://t.me/botfather>`_ and get the **bot token**.

To configure the bot just **open the config.yml file
and insert your token** (without double quotes or single quotes).

.. code:: yml

    token: your token here

*optional:*

changing the text in the bot

*example*:

.. code:: yml

    notbot_text: Ok {}, you're not a bot.

where you see the curly bracket it will be insert the name of the person that joins the group.

============
Starting
============

Open the powershell or whatever shell you want,
navigate to the bot root:

.. code:: shell

    $ cd im-not-a-bot

Start the bot with:

.. code:: shell

    $ python bot.py

Now you can add you bot to a supergroup and make it administrator.

**Done**, now when someone joins the group he will be restricted and prompted to press the button to confirm that he's not a bot.