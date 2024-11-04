#!/bin/sh
# Install Aapanel trên Ubuntu 22.04

nano script.sh : tạo ra file mới rồi copy hết dữ liệu trên file install_7.0_en vào 
Ctrl + O rồi Enter để lưu file
Ctrl + X để thoát 

chmod +x script.sh :cấp quyền thực thi

bash script.s.sh :chạy file script mới tạo


# Hoặc

Ubuntu
sudo apt-get update -y && sudo apt-get upgrade -y
sudo apt-get install wget
wget -O install_7.0_en.sh https://github.com/income88/AAPanel-Server/install_7.0_en.sh && sudo bash install_7.0_en.sh

Cenos 
yum install -y wget && wget -O install_7.0_en.sh https://github.com/income88/AAPanel-Server/install_7.0_en.sh && bash install_7.0_en.sh

