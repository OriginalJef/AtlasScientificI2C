POOLBOT
==================================

	AtlasScientificI2C/
	├── src/
	│	├── i2c.py
	└── README.md


## Info

- Contributor: **Jef Roosens**
- Source: [Atlas Scientific](https://github.com/AtlasScientific/Raspberry-Pi-sample-code/blob/master/i2c.py)

I did reform this script to make it work in Python3

## Deploy

### Clone

```
$ cd ~/Code/
```

```
$ git clone https://github.com/OriginalJef/AtlasScientificI2C.git

```

### Settings Raspberry Pi

```
$ sudo raspi-config
```
Interfacing Option > P5 I2C | Enable

### Install required packages on the Raspberry Pi

```
$ sudo apt-get update
```

```
$ sudo apt-get upgrade
```

```
$ sudo apt-get install python-smbus i2c-tools
```

## Execute script on Raspberry Pi

```
$ cd AtlacScientificI2C/src
```

```
$ python3 app.py
```
