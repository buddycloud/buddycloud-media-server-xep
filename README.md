buddycloud-xep
==============

This XEP defines the XMPP protocol for buddycloud servers and clients.

Built using https://github.com/lloydwatkin/xep-builder

## Building the XEP

```bash
make
open index.html
```

## Editing the XEP

XEP sections are held in the subdirectory. Edit these as appropriate and then build as above.

When files are pushed to the master branch in buddycloud/buddycloud-media-server-xep if valid travis-ci will build the HTML file and deploy to the URLs below.

### Building the XEP as you work

```
npm install -g grunt-cli
npm i .
grunt
```

Every time you now edit an xml file the XEP will be rebuilt

## Build status

[![Build Status](https://travis-ci.org/buddycloud/buddycloud-media-server-xep.png?branch=gh-pages)](https://travis-ci.org/buddycloud/buddycloud-media-server-xep)

http://buddycloud.github.io/buddycloud-media-server-xep/

