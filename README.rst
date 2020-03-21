.. image:: https://github.com/NicKoehler/im-not-a-bot/blob/master/logo/im-not-a-bot.png?raw=true
   :align: center
   :alt: im-not-a-bot Logo

Sections
=================

- `Introduction`_

- `Installing`_

- `Configure`_

- `Starting`_

Introduction
============

I'M SORRY FOR MY ENGLISH ON THIS PROJECT, **I'M ITALIAN** AND I CAN'T WRITE ENGLISH PERFECTLY.
IF YOU FIND TYPOS, ECC YOU CAN **`CONTACT ME <t.me/nickoehler>`_**.

This bot it's just a simple implementation of
a captcha for everyone that joins a telegram group.

Tested only with python 3.7

Installing
==========

Install im-not-a-bot cloning this repo:

    $ git clone https://github.com/NicKoehler/im-not-a-bot

Then install the requirements:

    $ pip install -r requirements.txt

Configure
==========

the first thing you need to do it's **create a telegram bot using the `bot father <t.me/botfather>`_** and get the **bot token**.

To configure the bot just **open the config.yml file
and insert your token** (without double quotes or single quotes).

    token: your token here

<i>optional:</i>

changing the text in the bot

<i>example</i>:

    notbot_text: Ok {}, you're not a bot.

where you see the curly bracket it will be insert the name of the person that joins the group.

Starting
==========

Open the powershell or whatever shell you want,
navigate to the bot root:

    $ cd im-not-a-bot

Start the bot with:

    $ python bot.py

Now you can add you bot to a supergroup and make it administrator.

**Done**, now when someone joins the group he will be restricted and prompted to press the button to confirm that he's not a bot.