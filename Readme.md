# Readme TYPO3 playground

This repo is a starting point/playground for [TYPO3 v9.5](https://typo3.org/), [ext:flux](https://github.com/FluidTYPO3/flux), 
[ext:fluidpages](https://github.com/FluidTYPO3/fluidpages), [ext:builder](https://github.com/FluidTYPO3/builder), 
[ext:extension-builder](https://github.com/FriendsOfTYPO3/extension_builder), 
[ext:blog](https://packagist.org/packages/t3g/blog) and [ext:vhs](https://github.com/FluidTYPO3/vhs) 
on an [DDEV Container-based environment](https://www.drud.com/) especialy utilizing
the PHPUnit [typo3/testing-framework](https://packagist.org/packages/typo3/testing-framework).

## Notes

* [setting up ddev (with docker) and TYPO3 installation with composer](readme/Readme-ddev.md)
* [setting up PHPUnit with typo3/test-framework](readme/Readme-phpunit.md)
* [ext:builder console command to create flux/fluidpages provider extension](readme/Readme-builder.md)
* [some notes to ext:extension_builder and to custom extension](readme/Readme-extension_builder.md)

## Quick install

> assuming git, ddev, docker and composer is installed on your machine

Tested on:

* Mac OS X 10.13.6 High Sierra
* Ubuntu 18.04.1 LTS

```
# lets start in your desired folder

$ git clone https://github.com/samowitsch/typo3-playground.git
$ cd typo3-playground
$ composer install
$ touch public/FIRST_INSTALL

# add to /etc/hosts
127.0.0.1 typo3-playground.ddev.local

$ ddev config
# follow onscreen instructions
# optional but recommended - change in file .ddev/config.yaml:
# ports: from 80/443 to 8000/8443
# webserver: from nginx-fpm to apache-fpm
$ ddev start

# open http://typo3-playground.ddev.local:8000
```
