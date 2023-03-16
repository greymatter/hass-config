# Welcome to my home assistant configuration #



## Frontend ##

I recently and am actually still in the process of implmenting most of the pieces of the Maximalist Front End by Madelena Mak.





Themes used (slightly adjusted):
- Metrogolgy - Based on vX.XX and then further Customized by myself, I've renamed to prevent wiping out any changes on future upgrades.

 

![](https://github.com/greymatter/hass-config/images/Network.png)


## Backend ##

### Addons ###
- [Samba Share](https://github.com/home-assistant/hassio-addons/tree/master/samba)
- [SSH & Web Terminal](https://github.com/home-assistant/hassio-addons/tree/master/ssh)
- [Unifi Network Application](https://github.com/hassio-addons/addon-unifi)
- [AdGuard Home](https://github.com/hassio-addons/addon-adguard-home)
- [Home Assistant Google Drive Backup](https://github.com/sabeechen/hassio-google-drive-backup)
- [Check HA Configuration](https://github.com/home-assistant/hassio-addons/tree/master/check_config)
- [Mosquitto Broker](https://github.com/home-assistant/hassio-addons/tree/master/mosquitto)
- [Deconz](https://github.com/home-assistant/hassio-addons/tree/master/deconz)
- [TimescaleDB](https://github.com/Expaso/hassos-addon-timescaledb)
- [DSMR Reader](https://github.com/sanderdw/hassio-addons)
- [pgAdmin 4](https://github.com/Expaso/hassos-addon-pgadmin4)
- [Eufy Security Addon](https://github.com/bropat/eufy-security-ws/tree/master/docker)
- [RTSP Simple Server Addon](http://192.168.99.3:8123/hassio)
- [Duck DNS](https://github.com/home-assistant/addons/tree/master/duckdns)
- [Nginx Proxy Manager](https://github.com/hassio-addons/addon-nginx-proxy-manager)
- [Maria DB](https://mariadb.com/)

### Integrations ###
- Adguard
- Browser_mod
- CO2 Signal
- DeCONZ
- Eufy Security
- Google Cast
- Google Home
- HACS
- Supervisor
- Roomba
- Kodi
- Meteorologisk Institutt
- Mobile App
- MQTT
- Risco
- Shelly
- Speedtest
- Spotify
- Unifi Network
- WebRTC Camera


### HACS (Home Assistant Community Store) ###

Integrations: 

- HACS
- Anniversaries
- WebRTC Camera
- Google Home
- Browser Mod
- Afvalbeheer
- Spotcast
- Sensor.Unifigateway
- Eufy Security
- Feedparser


Plugins:

- Battery State Card
- Button Card
- Atomic Calendar Revive
- Layout-card
- Vertical-stack-in-card
- Card-mod
- Homekit panel card
- Mini media player
- Check button card
- Swipe card
- Decluttering card
- Kiosk mode
- Stack-in-card
- Config-template-card
- Custom-ui
- ApexCharts
- More-info-card
- Multiple-entity-row
- Shutter Card
- Text Element
- Weather Card
- Media player popup card
- Sidebar card
- List card

## Devices ##

### Network ###
- [Unifi USG](https://www.ui.com/unifi-routing/usg/)
- [Unifi 16 PoE Switch](https://www.ui.com/unifi-switching/unifi-switch-16-150w/)
- [Unifi Access Points](https://www.ui.com/unifi/unifi-ap-ac-lite/)

### System ###
My system is a [Raspberry Pi 4B+ with 4 gig RAM](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/) running [Raspbian](https://www.raspberrypi.org/downloads/raspbian/).
All data is on a SSD.


### Gateways ###
- [ConBee II](https://phoscon.de/en/conbee2)
- [Velux KLF200](https://www.velux.be/nl-be/producten/smart-home/integra-accessoires?consent=preferences,statistics,marketing&ref-original=https%3A%2F%2Fwww.google.com%2F)

### Tablet ###

- Running [Fully Kiosk Browser](https://www.fully-kiosk.com/) on a samsung galaxy Tab S3 as central point in my living room. Screen comes on when i'm in front of it. It automatically switches off, as soon as i walk away. Powered with [this](https://www.robbshop.nl/scharge-oplader-voor-inbouwdoos-met-usb-c-12w-aansluiting-voor-ipad-pro?sqr=scharge%20usb&) attached to the wall with a  [Vogel mount](https://www.vogels.com/nl-be/c/tms-1010-muurpakket-voor-tablets).

### Smart Speakers ###
- [1x Google Nest Hub Max](https://store.google.com/us/product/google_nest_hub_max?hl=en-US)
- [4x Google Nest Hub](https://store.google.com/be/product/google_nest_hub?hl=nl-BE)
- [1x Google Home Mini](https://store.google.com/be/product/google_nest_mini?hl=nl-BE)
- [1x JBL Link Music](https://be.jbl.com/smart-speaker/LINK+MUSIC.html?dwvar_LINK%20MUSIC_color=Brown-EMEA-Current&cgid=smart-speaker#start=1)
- [1x JBL Bar 9.1](https://be.jbl.com/soundbars/JBL+BAR+9.1+TWS-.html?dwvar_JBL%20BAR%209.1%20TWS-_color=Black-EMEA-Current&cgid=Soundbars#start=1)


### Lights ###
- [Philips Hue GU10](https://www2.meethue.com/nl-be/p/hue-white-ambiance-2-pack-gu10/8718699629298)
- [Philips Hue E14](https://www2.meethue.com/nl-be/p/hue-white-ambiance-losse-kaarslamp-e14-duopak/8718696695265)
- [Philips Hue E27](https://www2.meethue.com/nl-be/p/hue-white-1-pack-e27/8718696785317)
- [Icasa Zigbee Dimmer](https://www.beaumotica.nl/icasa-iczb-iw11d-ac-dimmer-7061257407014)
- [Icasa Zigbee Switch](https://www.beaumotica.nl/icasa-iczb-iw11sw-ac-switch-7104389273352)
- [1x 0-10V Zigbee Dimmer](https://nl.aliexpress.com/item/10000015907761.html?spm=a2g0s.9042311.0.0.5e474c4dpS99hs)



### Sensors ###
- [4x Aqara door/window sensors](https://www.xiaomiproducts.nl/xiaomi-aqara-deur-en-raam-sensor-104834619.html)
- [3x Hue Motion Sensors](https://www.philips-hue.com/nl-be/p/hue-bewegingssensor/8718696743171)

### Plugs ###
- [5x Blitzwolf Smart Plugs](https://m.blitzwolf.com/ZigBee-3.0-Smart-Socket-EU-p-518.html)
- [2x Innr SP120 Plugs](https://www.beaumotica.nl/innr-smart-plug-aan-uit-schakelaar-doorsteek-stekker)
- [1x Silvercrest outdoor smart socket](https://evergreenproductinfo.com/2021/09/28/silvercrest-garden-spike-with-2-zigbee-smart-home-socketsfunctions-control-with-lidl-home-appwireless-connection-protocol-zigbee-3-0-output-16-a-230-v-3680-w-max/)


### Other ###
- [Unipi Neuron M203](https://www.unipi.technology/unipi-neuron-m203-p97)
- [Unipi Extension xS11](https://www.unipi.technology/unipi-extension-xs11-p336?categoryId=40)
- [1 x Shelly EM to monitor solarpanels](https://shelly.cloud/products/shelly-em-smart-home-automation-device/)


## Ordered ##

Nothing


## Automations ##

Coming




## Inspiration ##

Inspiration and code was taken from many different sources:

- [Troetelbeer](https://github.com/ddhatablet/hass-config)
- [Duboisph](https://github.com/duboisph/home-assistant-config)
- [Hmmbob](https://github.com/hmmbob/HomeAssistantConfig)
- [Basnijholt](https://github.com/basnijholt/home-assistant-config)
- [Pinkywafer](https://github.com/pinkywafer/Home-Assistant_Config)
