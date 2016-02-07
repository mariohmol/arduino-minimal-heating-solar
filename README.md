# arduino-minimal-heating-solar

How to use minimal resources in Arduino to configure a widget to heat your pool using solar energy.

## Arduino

You will need just:

* Arduino Uno or similar (with power cabble + USB cable to configure )
* One Relay 
* One potentionmeter
* 6 wires
* Small breadboard


### Libs

You have to install those libraries:

* https://github.com/PaulStoffregen/Time
   * DateTime and DatetTimeStrings

### Install

Load TimeHeating that can be found here


## Runnning

When you turn on the Arduino it will:

* Blink internal led indicating the current hour. So if is 8am it will blink 8 times
* Then after 3 seconds with led off, it will turn on for 3 seconds.
* After that it will take 3 seconds off and then blink how many times it will activate the motor in the current hour.
