## Prepare for Python development
`$ sudo apt install lsb-release build-essential git git-core \
    exuberant-ctags virtualenvwrapper python-virtualenv python3-virtualenv \
    python-dev python3-dev`  
`$ export WORKON_HOME=~/Envs`  
`$ mkdir -p $WORKON_HOME`  
`$ source /usr/local/bin/virtualenvwrapper.sh`  
`$ mkvirtualenv env1`  
[Virtual environment](https://virtualenvwrapper.readthedocs.io/en/latest/)
## GPIO in Python
[Raspberrypi page](https://www.raspberrypi.org/documentation/usage/gpio/python/README.md)
### GPIO Libaries
* [gpiozero](https://gpiozero.readthedocs.io/en/stable/)
* [RPi.GPIO](https://pypi.org/project/RPi.GPIO/)
* [raspberry-gpio-python](https://sourceforge.net/p/raspberry-gpio-python/wiki/Home/)
* [pigpio](https://pypi.org/project/pigpio/)  

[GPIO pin numbering](https://gpiozero.readthedocs.io/en/stable/recipes.html#pin-numbering)
#### Install GPIO Zero
[how-to](https://gpiozero.readthedocs.io/en/stable/installing.html#installing-gpio-zero)
#### I2C
[I2C python](https://www.instructables.com/id/Raspberry-Pi-I2C-Python/)
