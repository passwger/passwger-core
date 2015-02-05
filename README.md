# Passwger
Status: Pre-alpha

Issues: [![Issues](https://img.shields.io/github/issues/passwger/passwger-core.svg?style=flat)](https://github.com/passwger/passwger-core/issues)

_A cross-platform password manager._

## Introduction

**Passwger** allows you to manage your password easily under **multiple Os** (**Mac, Windows, Linux**).

## Screenshots

### Client

![Passwger Password Unlock](https://raw.githubusercontent.com/passwger/passwger-core/master/screenshots/screen4.png)

![Passwger Password Entry](https://raw.githubusercontent.com/passwger/passwger-core/master/screenshots/screen5.png)


## Features

- multi-OS client
- multi browser integration
- AES 256 encryption
- locally stored database (but you can sync using dropbox, google drive, etc)
- material design
- https connection for plugins (http://www.akadia.com/services/ssh_test_certificate.html)

## Downloads

### Client
n/a

### Browser plugin
n/a

## Instructions
In order to start to give a try to the project, once cloned you have to:

```
cd passwger-clone
npm install
cd dev
npm install
bower install
cd ..
node builder.js
```

Once built you can start using the OSX64 binary in the build folder, if you want to test under different Os you have to tweak the builder.js file.


## Thanks to
Proudly developed thanks to other projects like:

- [Node-Webkit](https://github.com/rogerwang/node-webkit)
- [MyDashboard](https://github.com/arvindr21/mydashboard)

## License

**Passwger** is licensed under MIT license.
