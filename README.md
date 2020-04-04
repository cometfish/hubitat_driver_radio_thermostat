# Radio Thermostat driver

Hubitat Driver for controlling [Radio Thermostat CT50](https://www.radiothermostat.com/product-page/ct50-wi-fi-smart-thermostat) (also known as Filtrete 3M-50) locally, with no hub or cloud connection required.  
This driver was ported from [statusbits' SmartThings driver](https://github.com/statusbits/smartthings).

1. Add `radio_thermostat.groovy` to your Hubitat as a new Driver (under `Drivers Code`)
2. Add a new device for your Thermostat to your Hubitat, set device Type to your User driver of 'Radio Thermostat'
3. Assign your thermostat a static IP, and enter the IP into the device's `Thermostat IP Address` setting in Hubitat.
5. Pressing Refresh on the device in Hubitat should now load the current state. Enjoy :)

Links:  
[statusbits' SmartThings driver](https://github.com/statusbits/smartthings)  
[Radio Thermostat API documentation](https://raw.githubusercontent.com/cometfish/hubitat_driver_radio_thermostat/master/docs/RTCOAWiFIAPIV1_3.pdf) (retrieved from the Wayback Machine archive of: https://radiothermostat.desk.com/customer/portal/kb_article_attachments/38350/original.pdf?1411231951 since Radio Thermostat have now taken down their support site and API documentation)

---

[![PayPal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ATTTMV7JV2W9W)

*If you enjoy using this software, please show your appreciation by making a small donation to the original author of the SmartThings driver (statusbits).*

---

### License

Copyright © 2014 Statusbits.com

This program is free software: you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the Free
Software Foundation, either version 3 of the License, or (at your option)
any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY
or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License
for more details.

You should have received a copy of the GNU General Public License along
with this program.  If not, see <http://www.gnu.org/licenses/>.
