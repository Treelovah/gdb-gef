# gdb-gef

## Script Install
Run the simple bash script that automates below steps with minimal error checking.

`bash INSTALL`

## Manual Installation
Run these commands:

`sudo apt install -y gdb python3-pip`

`pip install keystone-engine unicorn capstone ropper'

`wget -O ~/.gdbinit-gef.py -q https://github.com/hugsy/gef/raw/master/gef.py`

`echo source ~/.gdbinit-gef.py >> ~/.gdbinit`
