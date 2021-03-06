[![pipeline status](https://gitlab.getweave.com/weave-lab/ops/Blueproximity/badges/master/pipeline.svg)](https://gitlab.getweave.com/weave-lab/ops/Blueproximity/commits/master)
[![coverage report](https://gitlab.getweave.com/weave-lab/ops/Blueproximity/badges/master/coverage.svg)](https://gitlab.getweave.com/weave-lab/ops/Blueproximity/commits/master)

## Installation
```bash
go get weavelab.xyz/Blueproximity
```

For more information on `weavelab.xyz`, see the projects [readme](https://gitlab.getweave.com/weave-lab/ops/xyz/blob/master/README.md).

Blueproximity [![Documentation Status](https://readthedocs.org/projects/blueproximity/badge/?version=latest)](http://blueproximity.readthedocs.io/en/latest/?badge=latest) [![Build Status](https://travis-ci.org/Thor77/Blueproximity.svg?branch=master)](https://travis-ci.org/Thor77/Blueproximity)
=============

[TODOs until reaching usable state](https://github.com/Thor77/Blueproximity/milestone/1)

This software helps you add a little more security to your
desktop. It does so by detecting one of your bluetooth devices,
most likely your mobile phone, and keeping track of its distance.

If you move away from your computer and the distance is above
a certain level (no measurement in meters is possible) for a
given time, it automatically locks your desktop
(or starts any other shell command you want).
See end of this file for interesting commands.

Once away your computer awaits its master back - if you are
nearer than a given level for a set time your computer unlocks
magically without any interaction
(or starts any other shell command you want).

See the doc/ directory or the website which both contain
a manual with screenshots.

Please note that there might still some bugs, use the sourceforge
site to keep track of them or tell me about new ones not mentioned
there.
Please read the whole manual - it's short enough, hopefully easy
understandable and hey - it even got some pretty pictures in there
too :-)

## Contributors
* Tobias Jakobs (GUI optimizations)
* Zsolt Mazolt (GUI and KDE stuff)
* christoss (Slovene translation)
* eljak (Arabic translation)
* byMeanMachine (Polish translation)

## Interesting commands
* Un-/Locking gnome-screenserver
    * `gnome-screensaver-command -l`
    * `gnome-screensaver-command -d`
* Telling GAIM your status
  * `gaim-remote "irc:setstatus?status=away&message=BlueProximity thinks I am away"`
  * `gaim-remote "irc:setstatus?status=available"`
