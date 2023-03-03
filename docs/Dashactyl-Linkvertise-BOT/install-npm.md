---
sidebar_position: 1
---

# Install Node and NPM

Download essential **dependencies** to make it work.

- [`Ubuntu`](#ubuntu-and-debian) → `>=20.04`
- [`Debian`](#ubuntu-and-debian) → `>=10`
- [`Windows`](#windows) → `>=10`

## Ubuntu and Debian

Firstly, make sure that you have all the prerequisites above installed (if you do you can skip this part).

```bash
# installing NPM
sudo apt install npm

# installing NodeJS
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo bash -
sudo apt install nodejs

#download modules
npm install
```

## Windows

First, make sure you have all the prerequisites listed at the top of the page (if you do you can skip this part).

- NPM and NodeJS v16: https://nodejs.org/en/

You can check the versions with the following commands:

```bat
npm -v
node -v
```

Now you can install the module using:

```bash
npm install
```
