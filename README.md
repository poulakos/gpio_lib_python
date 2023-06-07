ASUS PYTHON GPIO LIB README 
===========================

#Download source code\
git clone https://github.com/TinkerBoard/gpio_lib_python.git

#Build\
 sudo apt-get install python3.9 python3.9-dev\
 cd ASUS_GPIO_PYTHON_PATH/gpio/\
 sudo CFLAGS="-fcommon" python3 setup.py install

#A Simple Python Program\
 import ASUS.GPIO as GPIO\
 GPIO.setmode(GPIO.ASUS)\
 GPIO.setup(17, GPIO.OUT)\
 GPIO.output(17, GPIO.HIGH)

#More Informaion\
 Send an email to scorpio_chang@asus.com
