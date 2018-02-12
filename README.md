[![ TSL2569](TSL2569_I2C.png)](https://store.ncd.io/product/tsl2569-16-bit-light-to-digital-converter-programmable-gain-i2c-mini-module/).

#  TSL2569

The TSL2569 is a light-to-digital converter that transforms light intensity to a digital signal output.
This Device is available from www.ncd.io 

[SKU: TSL2569]

(https://store.ncd.io/product/tsl2569-16-bit-light-to-digital-converter-programmable-gain-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface TSL2569 16Bit light to digital converter sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/tsl2569-16-bit-light-to-digital-converter-programmable-gain-i2c-mini-module/">TSL2569 16Bit light to digital converter sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python TSL2569.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
