---
layout: post
title: Setting up OpenSSH on CrunchBang Linux
description: "Setting up OpenSSH on CrunchBang Linux"
modified: 2014-07-17
tags: [openssh server, ssh, setup, crunchbang]
image:
  feature: abstract-3.jpg
  credit: dargadgetz
  creditlink: http://www.dargadgetz.com/ios-7-abstract-wallpaper-pack-for-iphone-5-and-ipod-touch-retina/
comments: true
share: true
---

When installing crunchbang I'm pretty sure I chose to install the OpenSSH server but somehow I when I did this again, it still installed for me. Hope it isn't installed twice for some stupid reason.

    sudo apt-get install openssh-server

and that was it. I can ssh in from my mac after that.

Follow instructions from [here](http://crunchbanglinux.org/wiki/howto/ssh)

When setting up ssh keys, there's no need to modify the sshd_config file as described on the page. It seems to work out of the box.
