Vapory Network Stats
============
[![Build Status][travis-image]][travis-url] [![dependency status][dep-image]][dep-url]

This is a visual interface for tracking vapory network status. It uses WebSockets to receive stats from running nodes and output them through an angular interface. It is the front-end implementation for [vap-net-intelligence-api](https://github.com/cubedro/vap-net-intelligence-api).

![Screenshot](https://raw.githubusercontent.com/vaporyco/vap-netstats/master/src/images/screenshot.jpg?v=0.0.6 "Screenshot")

## Prerequisite
* node
* npm

## Installation
Make sure you have node.js and npm installed.

Clone the repository and install the dependencies

```bash
git clone https://github.com/vaporyco/vap-netstats
cd vap-netstats
npm install
sudo npm install -g grunt-cli
```

##Build the resources
NetStats features two versions: the full version and the lite version. In order to build the static files you have to run grunt tasks which will generate dist or dist-lite directories containing the js and css files, fonts and images.


To build the full version run
```bash
grunt
```

To build the lite version run
```bash
grunt lite
```

If you want to build both versions run
```bash
grunt all
```

##Run

```bash
npm start
```

see the interface at http://localhost:3000

[travis-image]: https://travis-ci.org/cubedro/vap-netstats.svg
[travis-url]: https://travis-ci.org/cubedro/vap-netstats
[dep-image]: https://david-dm.org/cubedro/vap-netstats.svg
[dep-url]: https://david-dm.org/cubedro/vap-netstats