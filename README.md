# Semantic-UI-RTL

RTL Build of Semantic UI


# Requirements

To use this repo you don't need any requirement.


# Build A Newser Version

### Requirements

To Build a newer RTL (bidirectional) version you need NodeJS, Gulp, and Ant.
We will demonstrate how to install these requirements on Debian.

To install Ant on Debian you just need to enter `apt-get install ant`.

Here is how you can install NodeJS in Debian:

```
apt-get install curl
curl --silent --location https://deb.nodesource.com/setup_6.x | bash -
apt-get install --yes nodejs
```

To install Gulp globally you can:

```
npm install -g gulp
```


### Build

To build a new version you just need to execute:

```
ant build
ant clean
```
