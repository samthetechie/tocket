tocket
======

![tocket-logo](https://raw.githubusercontent.com/samthetechie/tocket/master/images/tocket-logo.png)

Description
-----------
Relay Switched Power Socket over a Tor Hidden Service

Build Photos
------------
http://samthetechie.blogspot.fr/2014/08/tocket-build-photos.html

Documentation
-------------

How to connect the Nanode to the programming cable: 
cp2102 pinout

Nanode -> cp2102 solder on a 1pin to the DTR line

RTS -> DTR

TXD -> rx

RXD -> tx

+5V -> 5V

0V -> gnd

Source: http://wiki.xinchejian.com/wiki/Nanode,_USB_FTDI,_OSX10.7

This project's codebase was forked from: https://wiki.london.hackspace.org.uk/view/Project:Nanode/Applications#Webserver_Application_with_Live_Analogue_Thermistor_Served_on_Webpage.28samthetechie_and_lambda25.29

This project uses the ipv4 stack / EtherShield library from: https://github.com/thiseldo/EtherShield
