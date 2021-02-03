# 2021 - Geckodriver-ARM
Geckodriver for last Raspbian 64 OS - Version 0.29

Geckodriver compiled for last update Raspbian OS 64 bits

Machine : Raspberry Pi 4 - 4 GB

Firefox : Firefox ESR - Version : 78.7.0 - 64 bits


Instructions:
  -Download it
  
  -Extract it
  
  -Give permissions : chmod 777 geckodriver
  
  -Copy to rute /usr/bin
  
  -sudo cp geckodriver /usr/bin
  
  -Add the path to your python script like this : 
  
  
      from selenium import webdriver

      from selenium.webdriver.firefox.options import Options

      from selenium.webdriver import Firefox

      options = Options()

      driver = webdriver.Firefox(options=options, executable_path="/usr/bin/geckodriver")
      
  -Enjoy it!
