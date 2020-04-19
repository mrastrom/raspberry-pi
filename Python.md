## Prepare for Python development
`$ sudo apt install lsb-release build-essential git git-core \    
    exuberant-ctags virtualenvwrapper python-virtualenv python3-virtualenv \    
    python-dev python3-dev`  
  
[Virtual environment wrapper](https://virtualenvwrapper.readthedocs.io/en/latest/)
1. Create a directory to hold the virtual environments.(mkdir ~/Envs).
2. Add a line like "export WORKON_HOME=~/Envs" to your .bashrc.
3. Add a line like "source /path/to/this/file/virtualenvwrapper.sh" to your .bashrc.
   Ex. usr/share/virtualenvwrapper/virtualenvwrapper.sh
4. Run: source ~/.bashrc
5. Run: workon
6. A list of environments, empty, is printed.
7. Run: mkvirtualenv temp
8. Run: workon
9. This time, the "temp" environment is included.
10. Run: workon temp
11. The virtual environment is activated    

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
