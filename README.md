#!/bin/sh
# Install Aapanel trên Ubuntu 22.04

cd /tmp/ && yum install git -y && git clone https://github.com/income88/AAPanel-Server && cd AAPanel-Server/ && sed -i -e 's/\r$//' install_7.0_en.sh && chmod 755 install_7.0_en.sh && ./install_7.0_en.sh
