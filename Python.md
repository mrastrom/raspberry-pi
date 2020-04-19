## Prepare for Python development
`$ sudo apt install lsb-release \`     
   `build-essential git git-core \`     
   `exuberant-ctags $ python3-pip\`          
   `python3-dev`  
   
 `$ sudo pip3 install virtualenvwrapper`
  
[Virtual environment wrapper](https://virtualenvwrapper.readthedocs.io/en/latest/)
1. Create a directory to hold the virtual environments.(mkdir ~/Envs).
2. Add a line like "export WORKON_HOME=~/Envs" to your .bashrc.
3. Add a line like "source /path/to/this/file/virtualenvwrapper.sh" to your .bashrc.
   Ex. /usr/local/bin/virtualenvwrapper.sh
4. Add a line like "export VIRTUALENVWRAPPER_ENV_BIN_DIR=bin"
5. Run: source ~/.bashrc
6. Run: workon
7. A list of environments, empty, is printed.
8. Run: mkvirtualenv temp
9. Run: workon
10. This time, the "temp" environment is included.
11. Run: workon temp
12. The virtual environment is activated    

#### .bashrc example
` ... `    
` ... `    
` ... `    
`export WORKON_HOME=~/Envs`    
`export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3`    
`export PROJECT_HOME=$HOME/develop`    
`source /usr/local/bin/virtualenvwrapper.sh`    
`export VIRTUALENVWRAPPER_ENV_BIN_DIR=bin`    

#### References
[virtualenvwrapper commands](https://virtualenvwrapper.readthedocs.io/en/latest/command_ref.html)
[Installing](https://medium.com/@gitudaniel/installing-virtualenvwrapper-for-python3-ad3dfea7c717)

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
