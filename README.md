# envirotemp

## Install

### Pi Setup
* Enable i2c: `raspi-config nonint do_i2c 0`
* Enable SPI: `raspi-config nonint do_spi 0`

```
sudo apt install python-numpy python-smbus python-pil python-setuptools
```

### Enviroplus libs
```
curl -sSL https://get.pimoroni.com/enviroplus | bash
```