# react-native with expo

## Installation

### Installing Node.JS

```bash
sudo apt update && sudo apt upgrade
```
```bash
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
```
```bash
sudo apt-get install nodejs
```
```bash
node -v
```
Output
> v12.22.9

### Installing Node Package Manager (NPM), which provides additional flexibility for Node.JS management

```bash
sudo apt install -y npm
```
```bash
npm -v
```
Output
> 8.5.1

### Installing expo-cli

```bash
sudo npm install -g expo-cli
```

### Installing Android-Studio

Installing JDK
```bash
sudo apt install openjdk-11-jdk
```
```bash
java --version
```
Output
> openjdk 11.0.19 2023-04-18

Installing android-studio from repository
```bash
sudo add-apt-repository ppa:maarten-fonville/android-studio
```
```bash
sudo apt update
```
```bash
sudo apt install android-studio -y
```


## Init app with expo-cli

```bash
expo init trekking-sj
```
```bash
cd trekking-sj
```
```bash
npm start
```
