bolt-svbtle
===========

Svbtle for the bolt CMS

## Installation
git clone git://github.com/bobdenotter/bolt.git bolt
cd bolt 
curl -s http://getcomposer.org/installer | php
php composer.phar install
git submodule add git://github.com/gmoigneu/bolt-svbtle.git theme/svbtle

## Options to add to config.yml :

author: Guillaume Moigneu
description: Lorem ipsum dolor.
typekitjs: tut2vyd
color: "#ff9c00"
icon: coffee
twitter: gmoigneu
github: gmoigneu
email: n@nls.io
google-analytics: UA-658246-20

## Modify contenttypes.yml
Add a "kudos" fields to the entries :

kudos:
            type: number