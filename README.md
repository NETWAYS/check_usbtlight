check_usbtlight
===============

Check USB traffic light.

http://shop.netways.de/alarmierung/nagios-ampel/nagios-usb-ampel-medium.html

### Requirements

Requires clewarecontrol from http://www.vanheusden.com/clewarecontrol
    
### Usage

    check_usbtlight.pl --url <url> [--user <user>] [--passwd <passwd>] [--hostgroup <hostgroup>] [--servicegroup <servicegroup>] 

       --url          url to nagios
       --user         nagios user for the webinterface
       --passwd       password for the nagios user
       --hostgroup    nagios hostgroup
       --servicegroup nagios servicegroup
       --debug        show debugging

