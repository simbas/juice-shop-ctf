# ![Juice Shop CTF Logo](https://raw.githubusercontent.com/bkimminich/juice-shop-ctf/master/images/JuiceShopCTF_Logo_100px.png) OWASP Juice Shop CTF [![OWASP Labs](https://img.shields.io/badge/owasp-lab%20project-f7b73c.svg)](https://www.owasp.org/index.php/OWASP_Project_Inventory#tab=Labs_Projects) [![GitHub release](https://img.shields.io/github/release/bkimminich/juice-shop-ctf.svg)](https://github.com/bkimminich/juice-shop-ctf/releases/latest) [![Twitter Follow](https://img.shields.io/twitter/follow/owasp_juiceshop.svg?style=social&label=Follow)](https://twitter.com/owasp_juiceshop)

[![Build Status](https://travis-ci.org/bkimminich/juice-shop-ctf.svg?branch=master)](https://travis-ci.org/bkimminich/juice-shop-ctf)
[![Coverage Status](https://coveralls.io/repos/github/bkimminich/juice-shop-ctf/badge.svg?branch=master)](https://coveralls.io/github/bkimminich/juice-shop-ctf?branch=master)
[![Code Climate](https://codeclimate.com/github/bkimminich/juice-shop-ctf/badges/gpa.svg)](https://codeclimate.com/github/bkimminich/juice-shop-ctf)
[![Dependency Status](https://gemnasium.com/badges/github.com/bkimminich/juice-shop-ctf.svg)](https://gemnasium.com/github.com/bkimminich/juice-shop-ctf)
[![Greenkeeper badge](https://badges.greenkeeper.io/bkimminich/juice-shop-ctf.svg)](https://greenkeeper.io/)

The NPM package
[`juice-shop-ctf-cli`](https://www.npmjs.com/package/juice-shop-ctf-cli)
lets you create a ZIP-archive compatible with [CTFd](https://ctfd.io)'s
data backup format to conveniently populate the platform for a
[Capture the Flag](https://en.wikipedia.org/wiki/Capture_the_flag#Computer_security)
event against
[OWASP Juice Shop](http://owasp-juice.shop).

![CLI in action](https://raw.githubusercontent.com/bkimminich/juice-shop-ctf/master/images/juice-shop-ctf-cli.animated.gif)

> :information_source: The data format generated by `v4.x` of this utility
> has been tested for schema-compatibility with
> [CTFd `≥v1.1.0`](https://github.com/CTFd/CTFd/releases/tag/1.1.0).

## Setup [![npm](https://img.shields.io/npm/dm/juice-shop-ctf-cli.svg)](https://www.npmjs.com/package/juice-shop-ctf-cli) [![npm](https://img.shields.io/npm/dt/juice-shop-ctf-cli.svg)](https://www.npmjs.com/package/juice-shop-ctf-cli)

```
npm install -g juice-shop-ctf-cli
```

## Usage

Open a command line and run:

```
juice-shop-ctf
```

Then follow the instructions of the interactive command line tool.

**For detailed step-by-step instructions and examples please refer to
[the _Setting up CTFd for Juice Shop_ in the _Hosting a CTF event_ chapter](https://bkimminich.gitbooks.io/pwning-owasp-juice-shop/content/part1/ctf.html#setting-up-ctfd-for-juice-shop)
of our (free) companion guide ebook.**

## Screenshots

![CTFd challenge overview](https://bkimminich.gitbooks.io/pwning-owasp-juice-shop/content/part1/img/ctfd_1.png)

![CTFd challenge details](https://bkimminich.gitbooks.io/pwning-owasp-juice-shop/content/part1/img/ctfd_2.png)

## Troubleshooting [![Gitter](http://img.shields.io/badge/gitter-join%20chat-1dce73.svg)](https://gitter.im/bkimminich/juice-shop)

> If you need help with the application setup please check the
> Troubleshooting section below or post your specific problem or
> question in the
> [official Gitter Chat](https://gitter.im/bkimminich/juice-shop).

- If using Docker Toolbox on Windows make sure that you also enable port
  forwarding for all required ports from Host `127.0.0.1:XXXX` to
  `0.0.0.0:XXXX` for TCP in the `default` VM's network adapter in
  VirtualBox. For CTFd you need to forward port `8000`.

## Contributing [![GitHub contributors](https://img.shields.io/github/contributors/bkimminich/juice-shop-ctf.svg)](https://github.com/bkimminich/juice-shop-ctf/graphs/contributors) [![Stories in Ready](https://badge.waffle.io/bkimminich/juice-shop.svg?label=ready&title=Ready)](http://waffle.io/bkimminich/juice-shop)

Found a bug? Got an idea for enhancement? Improvement for cheating
prevention?

Feel free to
[create an issue](https://github.com/bkimminich/juice-shop-ctf/issues)
or
[post your ideas in the chat](https://gitter.im/bkimminich/juice-shop)!
Pull requests are also highly welcome - please refer to
[CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Donations

### PayPal [![PayPal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=paypal%40owasp%2eorg&lc=BM&item_name=OWASP%20Juice%20Shop%20Project&item_number=OWASP%20Foundation&no_note=0&currency_code=USD&bn=PP%2dDonationsBF)

PayPal donations via above button go to the OWASP Foundations and are
earmarked for "Juice Shop". This is the preferred way to support the
project.

### Others

[![Flattr](https://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/thing/3856930/bkimminichjuice-shop-on-GitHub)
[![Gratipay](http://img.shields.io/gratipay/team/juice-shop.svg)](https://gratipay.com/juice-shop)

[![Bitcoin](https://img.shields.io/badge/bitcoin-1AbKfgvw9psQ41NbLi8kufDQTezwG8DRZm-orange.svg)](https://blockchain.info/address/1AbKfgvw9psQ41NbLi8kufDQTezwG8DRZm)
[![Dash](https://img.shields.io/badge/dash-Xr556RzuwX6hg5EGpkybbv5RanJoZN17kW-blue.svg)](https://explorer.dash.org/address/Xr556RzuwX6hg5EGpkybbv5RanJoZN17kW)
[![Ether](https://img.shields.io/badge/ether-0x0f933ab9fcaaa782d0279c300d73750e1311eae6-lightgrey.svg)](https://etherscan.io/address/0x0f933ab9fcaaa782d0279c300d73750e1311eae6)

## Contributors

### Collaborators

- [Björn Kimminich](https://github.com/bkimminich) aka `bkimminich`
  (Project Leader)
- [Jannik Hollenbach](https://github.com/J12934) aka `J12934`
- [Timo Pagel](https://github.com/wurstbrot) aka `wurstbrot`

### Code Contributors

Based on [GitHub](https://github.com/bkimminich/juice-shop-ctf) commits.
Ordered by added lines of code as of Mon, 11 Dec 2017 on `master`.

- [Josh Grossman](https://github.com/tghosth) aka `tghosth`

## Licensing [![license](https://img.shields.io/github/license/bkimminich/juice-shop-ctf-server.svg)](LICENSE)

This program is free software: you can redistribute it and/or modify it
under the terms of the [MIT license](LICENSE). OWASP Juice Shop and any
contributions are Copyright © by Bjoern Kimminich 2016-2018.

![Juice Shop CTF Logo](https://raw.githubusercontent.com/bkimminich/juice-shop-ctf/develop/images/JuiceShopCTF_Logo.png)
