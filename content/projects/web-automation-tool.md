---
title: "Web Automation with Notifications"
date: 2022-07-04T07:48:02+02:00
draft: false
---

#### Overview:
Python scripts to automate tasks on the browser. Useful for sites that do not have notifications or waiting lists. Goal is to avoid manual polling. Notifications on every platform thanks to an slack bot included.

#### Project State:
In development.

#### Used Technologies: 

* [python](https://www.python.org/) for the scripts
* [selenium](https://www.selenium.dev/) as the core library to control the browser
* [helium](https://github.com/mherrmann/selenium-python-helium) as an abstraction layer to interact with selenium
* [bolt for python](https://api.slack.com/start/building/bolt-python) as the framework for the slack bot usind websocket
* [slack API](https://api.slack.com/)


#### TODOs

* add more interactions with the slack bot.
* let the used decide on an action based on a slack button.
* trigger different functions based on the message send to the slack bot.

#### Source: 
The source code can be found on my [github](https://github.com/Nzalo/webautomation-examples).