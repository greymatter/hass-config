
# Welcome wave!

This is my Home Assistant installation.

## Some statistics about my installation:

Description | value
--|--
Installed version | unknown
Total entity objects | 2902
Entities in the [`alarm_control_panel`](https://www.home-assistant.io/components/alarm_control_panel) domain | 2
Entities in the [`alert`](https://www.home-assistant.io/components/alert) domain | 2
Entities in the [`automation`](https://www.home-assistant.io/components/automation) domain | 53
Entities in the [`binary_sensor`](https://www.home-assistant.io/components/binary_sensor) domain | 231
Entities in the [`button`](https://www.home-assistant.io/components/button) domain | 61
Entities in the [`calendar`](https://www.home-assistant.io/components/calendar) domain | 10
Entities in the [`camera`](https://www.home-assistant.io/components/camera) domain | 15
Entities in the [`climate`](https://www.home-assistant.io/components/climate) domain | 1
Entities in the [`device_tracker`](https://www.home-assistant.io/components/device_tracker) domain | 10
Entities in the [`geo_location`](https://www.home-assistant.io/components/geo_location) domain | 2
Entities in the [`group`](https://www.home-assistant.io/components/group) domain | 91
Entities in the [`humidifier`](https://www.home-assistant.io/components/humidifier) domain | 1
Entities in the [`input_boolean`](https://www.home-assistant.io/components/input_boolean) domain | 21
Entities in the [`input_button`](https://www.home-assistant.io/components/input_button) domain | 46
Entities in the [`input_datetime`](https://www.home-assistant.io/components/input_datetime) domain | 6
Entities in the [`input_number`](https://www.home-assistant.io/components/input_number) domain | 16
Entities in the [`input_select`](https://www.home-assistant.io/components/input_select) domain | 4
Entities in the [`input_text`](https://www.home-assistant.io/components/input_text) domain | 47
Entities in the [`light`](https://www.home-assistant.io/components/light) domain | 37
Entities in the [`media_player`](https://www.home-assistant.io/components/media_player) domain | 47
Entities in the [`number`](https://www.home-assistant.io/components/number) domain | 24
Entities in the [`persistent_notification`](https://www.home-assistant.io/components/persistent_notification) domain | 1
Entities in the [`person`](https://www.home-assistant.io/components/person) domain | 3
Entities in the [`remote`](https://www.home-assistant.io/components/remote) domain | 1
Entities in the [`scene`](https://www.home-assistant.io/components/scene) domain | 52
Entities in the [`script`](https://www.home-assistant.io/components/script) domain | 14
Entities in the [`select`](https://www.home-assistant.io/components/select) domain | 27
Entities in the [`sensor`](https://www.home-assistant.io/components/sensor) domain | 1859
Entities in the [`sun`](https://www.home-assistant.io/components/sun) domain | 1
Entities in the [`switch`](https://www.home-assistant.io/components/switch) domain | 123
Entities in the [`update`](https://www.home-assistant.io/components/update) domain | 70
Entities in the [`vacuum`](https://www.home-assistant.io/components/vacuum) domain | 6
Entities in the [`variable`](https://www.home-assistant.io/components/variable) domain | 1
Entities in the [`weather`](https://www.home-assistant.io/components/weather) domain | 8
Entities in the [`zone`](https://www.home-assistant.io/components/zone) domain | 9

## Core integrations that I use

Integration | Configuration
--|--
[<img src="https://brands.home-assistant.io/_/adguard/icon.png" height="24"/>](https://brands.home-assistant.io/_/adguard/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/adguard/icon.png" height="24"/>](https://brands.home-assistant.io/_/adguard/icon.png#gh-light-mode-only) [Pihole](https://home-assistant.io/integrations/adguard) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/kodi/icon.png" height="24"/>](https://brands.home-assistant.io/_/kodi/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/kodi/icon.png" height="24"/>](https://brands.home-assistant.io/_/kodi/icon.png#gh-light-mode-only) [Kodi](https://home-assistant.io/integrations/kodi) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/automation/icon.png" height="24"/>](https://brands.home-assistant.io/_/automation/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/automation/icon.png" height="24"/>](https://brands.home-assistant.io/_/automation/icon.png#gh-light-mode-only) [Automation](https://home-assistant.io/integrations/automation) | [./cfg/automations.yaml](./cfg/automations.yaml)
[<img src="https://brands.home-assistant.io/_/sonofflan/icon.png" height="24"/>](https://brands.home-assistant.io/_/sonofflan/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/sonofflan/icon.png" height="24"/>](https://brands.home-assistant.io/_/sonofflan/icon.png#gh-light-mode-only) [SonoffLan](https://home-assistant.io/integrations/sonofflan) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/cast/icon.png" height="24"/>](https://brands.home-assistant.io/_/cast/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/cast/icon.png" height="24"/>](https://brands.home-assistant.io/_/cast/icon.png#gh-light-mode-only) [Google Cast](https://home-assistant.io/integrations/cast) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/cloudflare/icon.png" height="24"/>](https://brands.home-assistant.io/_/cloudflare/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/cloudflare/icon.png" height="24"/>](https://brands.home-assistant.io/_/cloudflare/icon.png#gh-light-mode-only) [Cloudflare](https://home-assistant.io/integrations/cloudflare) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/default_config/icon.png" height="24"/>](https://brands.home-assistant.io/_/default_config/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/default_config/icon.png" height="24"/>](https://brands.home-assistant.io/_/default_config/icon.png#gh-light-mode-only) [Default Config](https://home-assistant.io/integrations/default_config) | [./configuration.yaml](./configuration.yaml)
[<img src="https://brands.home-assistant.io/_/frontend/icon.png" height="24"/>](https://brands.home-assistant.io/_/frontend/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/frontend/icon.png" height="24"/>](https://brands.home-assistant.io/_/frontend/icon.png#gh-light-mode-only) [Frontend](https://home-assistant.io/integrations/frontend) | [./packages/integrations/core/frontend.yaml](./packages/integrations/core/frontend.yaml)
[<img src="https://brands.home-assistant.io/_/github/icon.png" height="24"/>](https://brands.home-assistant.io/_/github/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/github/icon.png" height="24"/>](https://brands.home-assistant.io/_/github/icon.png#gh-light-mode-only) [GitHub](https://home-assistant.io/integrations/github) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/influxdb/icon.png" height="24"/>](https://brands.home-assistant.io/_/influxdb/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/influxdb/icon.png" height="24"/>](https://brands.home-assistant.io/_/influxdb/icon.png#gh-light-mode-only) [InfluxDB](https://home-assistant.io/integrations/influxdb) | [./cfg/influxdb.yaml](./cfg/influxdb.yaml)
[<img src="https://brands.home-assistant.io/_/BlueIris/icon.png" height="24"/>](https://brands.home-assistant.io/_/BlueIris/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/BlueIris/icon.png" height="24"/>](https://brands.home-assistant.io/_/BlueIris/icon.png#gh-light-mode-only) [BlueIris NVR](https://home-assistant.io/integrations/BlueIris) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/logger/icon.png" height="24"/>](https://brands.home-assistant.io/_/logger/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/logger/icon.png" height="24"/>](https://brands.home-assistant.io/_/logger/icon.png#gh-light-mode-only) [Logger](https://home-assistant.io/integrations/logger) | [./cfg/logger.yaml](./cfg/logger.yaml)
[<img src="https://brands.home-assistant.io/_/met/icon.png" height="24"/>](https://brands.home-assistant.io/_/met/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/met/icon.png" height="24"/>](https://brands.home-assistant.io/_/met/icon.png#gh-light-mode-only) [Met.no](https://home-assistant.io/integrations/met) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/mobile_app/icon.png" height="24"/>](https://brands.home-assistant.io/_/mobile_app/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/mobile_app/icon.png" height="24"/>](https://brands.home-assistant.io/_/mobile_app/icon.png#gh-light-mode-only) [Mobile App](https://home-assistant.io/integrations/mobile_app) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/nanoleaf/icon.png" height="24"/>](https://brands.home-assistant.io/_/nanoleaf/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/nanoleaf/icon.png" height="24"/>](https://brands.home-assistant.io/_/nanoleaf/icon.png#gh-light-mode-only) [Nanoleaf](https://home-assistant.io/integrations/nanoleaf) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/netatmo/icon.png" height="24"/>](https://brands.home-assistant.io/_/netatmo/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/netatmo/icon.png" height="24"/>](https://brands.home-assistant.io/_/netatmo/icon.png#gh-light-mode-only) [Netatmo](https://home-assistant.io/integrations/netatmo) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/tomorrowio/icon.png" height="24"/>](https://brands.home-assistant.io/_/tomorrowio/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/tomorrowio/icon.png" height="24"/>](https://brands.home-assistant.io/_/tomorrowio/icon.png#gh-light-mode-only) [Tomorrow.io](https://home-assistant.io/integrations/tomorrowio) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/rest/icon.png" height="24"/>](https://brands.home-assistant.io/_/rest/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/rest/icon.png" height="24"/>](https://brands.home-assistant.io/_/rest/icon.png#gh-light-mode-only) [Rest](https://home-assistant.io/integrations/rest) | [./cfg/rest.yaml](./cfg/rest.yaml)
[<img src="https://brands.home-assistant.io/_/script/icon.png" height="24"/>](https://brands.home-assistant.io/_/script/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/script/icon.png" height="24"/>](https://brands.home-assistant.io/_/script/icon.png#gh-light-mode-only) [Script](https://home-assistant.io/integrations/script) | [./cfg/scripts.yaml](./cfg/scripts.yaml)
[<img src="https://brands.home-assistant.io/_/sentry/icon.png" height="24"/>](https://brands.home-assistant.io/_/sentry/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/sentry/icon.png" height="24"/>](https://brands.home-assistant.io/_/sentry/icon.png#gh-light-mode-only) [Sentry](https://home-assistant.io/integrations/sentry) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/spotify/icon.png" height="24"/>](https://brands.home-assistant.io/_/spotify/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/spotify/icon.png" height="24"/>](https://brands.home-assistant.io/_/spotify/icon.png#gh-light-mode-only) [Spotify](https://home-assistant.io/integrations/spotify) | [./cfg/spotify.yaml](./cfg/spotify.yaml)
[<img src="https://brands.home-assistant.io/_/hassio/icon.png" height="24"/>](https://brands.home-assistant.io/_/hassio/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/hassio/icon.png" height="24"/>](https://brands.home-assistant.io/_/hassio/icon.png#gh-light-mode-only) [Supervisor](https://home-assistant.io/integrations/hassio) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/telegram/icon.png" height="24"/>](https://brands.home-assistant.io/_/telegram/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/telegram/icon.png" height="24"/>](https://brands.home-assistant.io/_/telegram/icon.png#gh-light-mode-only) [Telegram BOT](https://home-assistant.io/integrations/telegram) | [./packages/integrations/core/telegram.yaml](./packages/integrations/core/telegram.yaml)
[<img src="https://brands.home-assistant.io/_/template/icon.png" height="24"/>](https://brands.home-assistant.io/_/template/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/template/icon.png" height="24"/>](https://brands.home-assistant.io/_/template/icon.png#gh-light-mode-only) [Template](https://home-assistant.io/integrations/template) | [./packages/integrations/core/template.yaml](./packages/integrations/core/template.yaml)
[<img src="https://brands.home-assistant.io/_/uptimekuma/icon.png" height="24"/>](https://brands.home-assistant.io/_/uptimekuma/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/uptimekuma/icon.png" height="24"/>](https://brands.home-assistant.io/_/uptimekuma/icon.png#gh-light-mode-only) [UptimeKuma](https://home-assistant.io/integrations/uptimekuma) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/version/icon.png" height="24"/>](https://brands.home-assistant.io/_/version/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/version/icon.png" height="24"/>](https://brands.home-assistant.io/_/version/icon.png#gh-light-mode-only) [Version](https://home-assistant.io/integrations/version) | Config flow[^1]
[<img src="https://brands.home-assistant.io/_/xiaomi_miio/icon.png" height="24"/>](https://brands.home-assistant.io/_/xiaomi_miio/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/xiaomi_miio/icon.png" height="24"/>](https://brands.home-assistant.io/_/xiaomi_miio/icon.png#gh-light-mode-only) [Xiaomi Miio](https://home-assistant.io/integrations/xiaomi_miio) | Config flow[^1]



## The custom integrations that I use

### [<img src="https://brands.home-assistant.io/_/hacs/icon.png" height="24"/>](https://brands.home-assistant.io/_/hacs/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/hacs/icon.png" height="24"/>](https://brands.home-assistant.io/_/hacs/icon.png#gh-light-mode-only) [HACS](https://github.com/hacs/integration)

_HACS gives you a powerful UI to handle downloads of all your custom needs._

**Version** | 1.31.0
--|--
**Author(s)** | @ludeeus

### [<img src="https://brands.home-assistant.io/_/bwalarm/icon.png" height="24"/>](https://brands.home-assistant.io/_/bwalarm/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/bwalarm/icon.png" height="24"/>](https://brands.home-assistant.io/_/bwalarm/icon.png#gh-light-mode-only) [Hass Custom Alarm](https://github.com/akasma74/Hass-Custom-Alarm)

_It is a fork of "Yet another take on a home assistant custom alarm" that will exist until its author is back to our Earth_


[**My configuration for Hass Custom Alarm**](./packages/integrations/custom/bwalarm.yaml)
**Version** | v.1.12.15
--|--
**Author(s)** | @akasma74

### [<img src="https://brands.home-assistant.io/_/sonoff/icon.png" height="24"/>](https://brands.home-assistant.io/_/sonoff/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/sonoff/icon.png" height="24"/>](https://brands.home-assistant.io/_/sonoff/icon.png#gh-light-mode-only) [Sonoff Lan](https://github.com/AlexxIT/SonoffLAN)

_Control Sonoff Devices with eWeLink (original) firmware over LAN and/or Cloud from Home Assistant_

**Version** | v3.4.0
--|--
**Author(s)** | @AlexxIT

### [<img src="https://brands.home-assistant.io/_/eventsensor/icon.png" height="24"/>](https://brands.home-assistant.io/_/eventsensor/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/eventsensor/icon.png" height="24"/>](https://brands.home-assistant.io/_/eventsensor/icon.png#gh-light-mode-only) [Event Sensor](https://github.com/azogue/eventsensor)

_HomeAssistant custom sensor to track specific events_

**Version** | v3.1.0
--|--
**Author(s)** | @azogue

### [<img src="https://brands.home-assistant.io/_/feedparser/icon.png" height="24"/>](https://brands.home-assistant.io/_/feedparser/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/feedparser/icon.png" height="24"/>](https://brands.home-assistant.io/_/feedparser/icon.png#gh-light-mode-only) [Feedparser](https://github.com/custom-components/feedparser)

_📰 RSS Feed Integration_


[**My configuration for Feedparser**](./packages/integrations/custom/feedparser.yaml)
**Version** | 0.1.9
--|--
**Author(s)** | @iantrich

### [<img src="https://brands.home-assistant.io/_/readme/icon.png" height="24"/>](https://brands.home-assistant.io/_/readme/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/readme/icon.png" height="24"/>](https://brands.home-assistant.io/_/readme/icon.png#gh-light-mode-only) [Generate Readme](https://github.com/custom-components/readme)

_Use Jinja and data from Home Assistant to generate your README.md file_

**Version** | 0.5.0
--|--
**Author(s)** | @ludeeus

### [<img src="https://brands.home-assistant.io/_/ssh/icon.png" height="24"/>](https://brands.home-assistant.io/_/ssh/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ssh/icon.png" height="24"/>](https://brands.home-assistant.io/_/ssh/icon.png#gh-light-mode-only) [Sensor.Ssh](https://github.com/custom-components/sensor.ssh)

_SSH Generic Sensor_


[**My configuration for Sensor.Ssh**](./packages/integrations/custom/ssh.yaml)
**Version** | 1.15
--|--
**Author(s)** | @jchasey

### [<img src="https://brands.home-assistant.io/_/spotcast/icon.png" height="24"/>](https://brands.home-assistant.io/_/spotcast/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/spotcast/icon.png" height="24"/>](https://brands.home-assistant.io/_/spotcast/icon.png#gh-light-mode-only) [Spotcast](https://github.com/fondberg/spotcast)

_Home assistant custom component to start Spotify playback on an idle chromecast device as well as control spotify connect devices_


[**My configuration for Spotcast**](./packages/integrations/custom/spotcast.yaml)
**Version** | v3.7.0
--|--
**Author(s)** | @fondberg

### [<img src="https://brands.home-assistant.io/_/ltss/icon.png" height="24"/>](https://brands.home-assistant.io/_/ltss/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ltss/icon.png" height="24"/>](https://brands.home-assistant.io/_/ltss/icon.png#gh-light-mode-only) [Ltss](https://github.com/freol35241/ltss)

_Long time state storage (LTSS) custom component for Home Assistant using Timescale DB_


[**My configuration for Ltss**](./packages/integrations/custom/ltss.yaml)
**Version** | v2.0.1
--|--
**Author(s)** | @freol35241

### [<img src="https://brands.home-assistant.io/_/cryptoinfo/icon.png" height="24"/>](https://brands.home-assistant.io/_/cryptoinfo/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/cryptoinfo/icon.png" height="24"/>](https://brands.home-assistant.io/_/cryptoinfo/icon.png#gh-light-mode-only) [Cryptoinfo](https://github.com/heyajohnny/cryptoinfo)

_Provides Home Assistant sensors for all cryptocurrencies supported by CoinGecko_


[**My configuration for Cryptoinfo**](./packages/integrations/custom/cryptoinfo.yaml)
**Version** | v0.1.4
--|--
**Author(s)** | @heyajohnny

### [<img src="https://brands.home-assistant.io/_/car_wash/icon.png" height="24"/>](https://brands.home-assistant.io/_/car_wash/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/car_wash/icon.png" height="24"/>](https://brands.home-assistant.io/_/car_wash/icon.png#gh-light-mode-only) [Car Wash](https://github.com/Limych/ha-car_wash)

_Car Wash Binary Sensor for Home Assistant_


[**My configuration for Car Wash**](./packages/integrations/custom/car_wash.yaml)
**Version** | 1.5.5
--|--
**Author(s)** | @Limych

### [<img src="https://brands.home-assistant.io/_/favicon/icon.png" height="24"/>](https://brands.home-assistant.io/_/favicon/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/favicon/icon.png" height="24"/>](https://brands.home-assistant.io/_/favicon/icon.png#gh-light-mode-only) [Hass Favicon](https://github.com/thomasloven/hass-favicon)

_🔹 Change the favicon of your Home Assistant instance_

**Version** | 10.4
--|--

### [<img src="https://brands.home-assistant.io/_/browser_mod/icon.png" height="24"/>](https://brands.home-assistant.io/_/browser_mod/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/browser_mod/icon.png" height="24"/>](https://brands.home-assistant.io/_/browser_mod/icon.png#gh-light-mode-only) [Browser Mod](https://github.com/thomasloven/hass-browser_mod)

_🔹 A Home Assistant integration to turn your browser into a controllable entity and media player_

**Version** | 2.2.0
--|--

### [<img src="https://brands.home-assistant.io/_/simpleicons/icon.png" height="24"/>](https://brands.home-assistant.io/_/simpleicons/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/simpleicons/icon.png" height="24"/>](https://brands.home-assistant.io/_/simpleicons/icon.png#gh-light-mode-only) [Simpleicons](https://github.com/vigonotion/hass-simpleicons)

_Use Simple Icons in Home Assistant_

**Version** | v2.2.0
--|--

### [<img src="https://brands.home-assistant.io/_/kodi_media_sensors/icon.png" height="24"/>](https://brands.home-assistant.io/_/kodi_media_sensors/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/kodi_media_sensors/icon.png" height="24"/>](https://brands.home-assistant.io/_/kodi_media_sensors/icon.png#gh-light-mode-only) [Kodi Media Sensors](https://github.com/jtbgroup/kodi-media-sensors)

_Custom component to feed multiple sensors in Home Assistan and so custom cards can be to display those sensors. This repository is a fork of https://github.com/boralyl/kodi-recently-added_

**Version** | 4.0.1
--|--
**Author(s)** | @boralyl, @Gautier Vanderslyen

### [<img src="https://brands.home-assistant.io/_/hdhomerun/icon.png" height="24"/>](https://brands.home-assistant.io/_/hdhomerun/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/hdhomerun/icon.png" height="24"/>](https://brands.home-assistant.io/_/hdhomerun/icon.png#gh-light-mode-only) [Hdhomerun](https://github.com/burnnat/ha-hdhomerun)

_HDHomeRun integration for Home Assistant._

**Version** | v0.0.7
--|--

### [<img src="https://brands.home-assistant.io/_/astroweather/icon.png" height="24"/>](https://brands.home-assistant.io/_/astroweather/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/astroweather/icon.png" height="24"/>](https://brands.home-assistant.io/_/astroweather/icon.png#gh-light-mode-only) [Astroweather](https://github.com/mawinkler/astroweather)

_Asynchronous Astro Weather Forecast for Home Assistant_

**Version** | v0.22.5
--|--
**Author(s)** | @mawinkler

### [<img src="https://brands.home-assistant.io/_/snowtire/icon.png" height="24"/>](https://brands.home-assistant.io/_/snowtire/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/snowtire/icon.png" height="24"/>](https://brands.home-assistant.io/_/snowtire/icon.png#gh-light-mode-only) [Snowtire Sensor](https://github.com/Limych/ha-snowtire)

_Home Assistant sensor to predict if it's time to change car tires from summer to winter and vice versa._


[**My configuration for Snowtire Sensor**](./packages/integrations/custom/snowtire.yaml)
**Version** | 1.4.5
--|--
**Author(s)** | @limych

### [<img src="https://brands.home-assistant.io/_/google_home/icon.png" height="24"/>](https://brands.home-assistant.io/_/google_home/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/google_home/icon.png" height="24"/>](https://brands.home-assistant.io/_/google_home/icon.png#gh-light-mode-only) [Google Home](https://github.com/leikoilja/ha-google-home)

_Home Assistant Google Home custom component _

**Version** | v1.9.17
--|--
**Author(s)** | @leikoilja, @DurgNomis-drol, @ArnyminerZ, @KapJI

### [<img src="https://brands.home-assistant.io/_/redfin/icon.png" height="24"/>](https://brands.home-assistant.io/_/redfin/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/redfin/icon.png" height="24"/>](https://brands.home-assistant.io/_/redfin/icon.png#gh-light-mode-only) [Redfin](https://github.com/dreed47/redfin)

_Redfin property estimate Sensor for Home Assistant_

**Version** | v1.1.4
--|--
**Author(s)** | @dreed47

### [<img src="https://brands.home-assistant.io/_/multiscrape/icon.png" height="24"/>](https://brands.home-assistant.io/_/multiscrape/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/multiscrape/icon.png" height="24"/>](https://brands.home-assistant.io/_/multiscrape/icon.png#gh-light-mode-only) [Multiscrape](https://github.com/danieldotnl/ha-multiscrape)

_Home Assistant custom component for scraping (html, xml or json) multiple values (from a single HTTP request) with a separate sensor/attribute for each value. Support for (login) form-submit functionality._


[**My configuration for Multiscrape**](./packages/integrations/custom/multiscrape.yaml)
**Version** | v6.6.1
--|--
**Author(s)** | @danieldotnl

### [<img src="https://brands.home-assistant.io/_/openweathermap_all/icon.png" height="24"/>](https://brands.home-assistant.io/_/openweathermap_all/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/openweathermap_all/icon.png" height="24"/>](https://brands.home-assistant.io/_/openweathermap_all/icon.png#gh-light-mode-only) [Openweathermap All](https://github.com/viktak/ha-cc-openweathermap_all)

_Home Assistant custom component combining multiple OpenWeatherMap API calls_


[**My configuration for Openweathermap All**](./packages/integrations/custom/openweathermap_all.yaml)
**Version** | None
--|--
**Author(s)** | @viktak

### [<img src="https://brands.home-assistant.io/_/helium/icon.png" height="24"/>](https://brands.home-assistant.io/_/helium/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/helium/icon.png" height="24"/>](https://brands.home-assistant.io/_/helium/icon.png#gh-light-mode-only) [Helium Blockchain](https://github.com/rsnodgrass/hass-helium)

_Helium blockchain sensors for Home Assistant_


[**My configuration for Helium Blockchain**](./packages/integrations/custom/helium.yaml)
**Version** | 0.3.8
--|--
**Author(s)** | @rsnodgrass

### [<img src="https://brands.home-assistant.io/_/powercalc/icon.png" height="24"/>](https://brands.home-assistant.io/_/powercalc/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/powercalc/icon.png" height="24"/>](https://brands.home-assistant.io/_/powercalc/icon.png#gh-light-mode-only) [Powercalc](https://github.com/bramstroker/homeassistant-powercalc)

_Custom component to calculate estimated power consumption of lights and other appliances_

**Version** | v1.3.12
--|--
**Author(s)** | @bramstroker

### [<img src="https://brands.home-assistant.io/_/variable/icon.png" height="24"/>](https://brands.home-assistant.io/_/variable/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/variable/icon.png" height="24"/>](https://brands.home-assistant.io/_/variable/icon.png#gh-light-mode-only) [Variables+History](https://github.com/Wibias/hass-variables)

_Home Assistant variables component_


[**My configuration for Variables+History**](./packages/integrations/custom/variable.yaml)
**Version** | 2.3.6
--|--
**Author(s)** | @rogro82, @wibias

### [<img src="https://brands.home-assistant.io/_/remote_homeassistant/icon.png" height="24"/>](https://brands.home-assistant.io/_/remote_homeassistant/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/remote_homeassistant/icon.png" height="24"/>](https://brands.home-assistant.io/_/remote_homeassistant/icon.png#gh-light-mode-only) [Remote Home Assistant](https://github.com/custom-components/remote_homeassistant)

_Links multiple home-assistant instances together_

**Version** | 3.8
--|--
**Author(s)** | @lukas-hetzenecker, @postlund

### [<img src="https://brands.home-assistant.io/_/nws_alerts/icon.png" height="24"/>](https://brands.home-assistant.io/_/nws_alerts/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/nws_alerts/icon.png" height="24"/>](https://brands.home-assistant.io/_/nws_alerts/icon.png#gh-light-mode-only) [Nws Alerts](https://github.com/finity69x2/nws_alerts)

_An updated version of the nws_alerts custom integration for Home Assistant_

**Version** | 2.8
--|--
**Author(s)** | @finity69x2

### [<img src="https://brands.home-assistant.io/_/garbage_collection/icon.png" height="24"/>](https://brands.home-assistant.io/_/garbage_collection/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/garbage_collection/icon.png" height="24"/>](https://brands.home-assistant.io/_/garbage_collection/icon.png#gh-light-mode-only) [Garbage Collection](https://github.com/bruxy70/Garbage-Collection)

_🗑 Custom Home Assistant sensor for scheduling garbage collection (or other regularly re-occurring events - weekly on given days, semi-weekly or monthly)_

**Version** | 4.10.2
--|--
**Author(s)** | @bruxy70

### [<img src="https://brands.home-assistant.io/_/hifiberry/icon.png" height="24"/>](https://brands.home-assistant.io/_/hifiberry/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/hifiberry/icon.png" height="24"/>](https://brands.home-assistant.io/_/hifiberry/icon.png#gh-light-mode-only) [Hifiberry](https://github.com/willholdoway/hifiberry)

_This is a custom component to allow control of HifiberryOS devices in Home Assistant using the audiocontrol2 REST API._

**Version** | None
--|--
**Author(s)** | @willholdoway, @dgomes

### [<img src="https://brands.home-assistant.io/_/grocy/icon.png" height="24"/>](https://brands.home-assistant.io/_/grocy/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/grocy/icon.png" height="24"/>](https://brands.home-assistant.io/_/grocy/icon.png#gh-light-mode-only) [Grocy Custom Component](https://github.com/custom-components/grocy)

_Custom Grocy integration for Home Assistant_

**Version** | v4.5.2
--|--
**Author(s)** | @SebRut, @isabellaalstrom

### [<img src="https://brands.home-assistant.io/_/yahoofinance/icon.png" height="24"/>](https://brands.home-assistant.io/_/yahoofinance/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/yahoofinance/icon.png" height="24"/>](https://brands.home-assistant.io/_/yahoofinance/icon.png#gh-light-mode-only) [Yahoo Finance](https://github.com/iprak/yahoofinance)

_Home Assistant component which allows you to get stock updates from Yahoo finance._


[**My configuration for Yahoo Finance**](./packages/integrations/custom/yahoofinance.yaml)
**Version** | v1.1.11
--|--
**Author(s)** | @iprak

### [<img src="https://brands.home-assistant.io/_/spacex/icon.png" height="24"/>](https://brands.home-assistant.io/_/spacex/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/spacex/icon.png" height="24"/>](https://brands.home-assistant.io/_/spacex/icon.png#gh-light-mode-only) [Spacex Next Launch And Starman](https://github.com/djtimca/HASpaceX)

_Home Assistant integration for SpaceX Next Launch and Starman data._

**Version** | 035
--|--
**Author(s)** | @djtimca

### [<img src="https://brands.home-assistant.io/_/blitzortung/icon.png" height="24"/>](https://brands.home-assistant.io/_/blitzortung/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/blitzortung/icon.png" height="24"/>](https://brands.home-assistant.io/_/blitzortung/icon.png#gh-light-mode-only) [Blitzortung.Org Lightning Detector](https://github.com/mrk-its/homeassistant-blitzortung)

_Custom Component for fetching lightning data from blitzortung.org_

**Version** | v1.3.1
--|--
**Author(s)** | @mrk-its

### [<img src="https://brands.home-assistant.io/_/waste_collection_schedule/icon.png" height="24"/>](https://brands.home-assistant.io/_/waste_collection_schedule/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/waste_collection_schedule/icon.png" height="24"/>](https://brands.home-assistant.io/_/waste_collection_schedule/icon.png#gh-light-mode-only) [Waste Collection Schedule](https://github.com/mampfes/hacs_waste_collection_schedule)

_Home Assistant integration framework for (garbage collection) schedules_


[**My configuration for Waste Collection Schedule**](./packages/integrations/custom/waste_collection_schedule.yaml)
**Version** | 1.37.0
--|--
**Author(s)** | @mampfes

### [<img src="https://brands.home-assistant.io/_/fontawesome/icon.png" height="24"/>](https://brands.home-assistant.io/_/fontawesome/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/fontawesome/icon.png" height="24"/>](https://brands.home-assistant.io/_/fontawesome/icon.png#gh-light-mode-only) [Fontawesome](https://github.com/thomasloven/hass-fontawesome)

_🔹 Use icons from fontawesome in home-assistant_

**Version** | 2.1.5
--|--

### [<img src="https://brands.home-assistant.io/_/kodi_recently_added/icon.png" height="24"/>](https://brands.home-assistant.io/_/kodi_recently_added/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/kodi_recently_added/icon.png" height="24"/>](https://brands.home-assistant.io/_/kodi_recently_added/icon.png#gh-light-mode-only) [Kodi Recently Added Media](https://github.com/boralyl/kodi-recently-added)

_Custom component to feed recently added tv shows and movies to the custom card "Upcoming Media Card" for Home Assistant. _

**Version** | v2.0.5
--|--
**Author(s)** | @boralyl

### [<img src="https://brands.home-assistant.io/_/scheduler/icon.png" height="24"/>](https://brands.home-assistant.io/_/scheduler/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/scheduler/icon.png" height="24"/>](https://brands.home-assistant.io/_/scheduler/icon.png#gh-light-mode-only) [Scheduler Component](https://github.com/nielsfaber/scheduler-component)

_Custom component for HA that enables the creation of scheduler entities_

**Version** | v3.2.14
--|--
**Author(s)** | @nielsfaber

### [<img src="https://brands.home-assistant.io/_/nodered/icon.png" height="24"/>](https://brands.home-assistant.io/_/nodered/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/nodered/icon.png" height="24"/>](https://brands.home-assistant.io/_/nodered/icon.png#gh-light-mode-only) [Node Red Companion](https://github.com/zachowj/hass-node-red)

_Companion Component for node-red-contrib-home-assistant-websocket to help integrate Node-RED with Home Assistant Core_

**Version** | v1.2.0
--|--
**Author(s)** | @zachowj

### [<img src="https://brands.home-assistant.io/_/satellitetracker/icon.png" height="24"/>](https://brands.home-assistant.io/_/satellitetracker/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/satellitetracker/icon.png" height="24"/>](https://brands.home-assistant.io/_/satellitetracker/icon.png#gh-light-mode-only) [Satellite Tracker (N2Yo)](https://github.com/djtimca/hasatellitetracker)

_Using the N2YO API, this Home Assistant integration will provide visible satellite passes (general) and to add specific satellites for monitoring._

**Version** | 0.0.8
--|--
**Author(s)** | @djtimca

### [<img src="https://brands.home-assistant.io/_/icloud3/icon.png" height="24"/>](https://brands.home-assistant.io/_/icloud3/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/icloud3/icon.png" height="24"/>](https://brands.home-assistant.io/_/icloud3/icon.png#gh-light-mode-only) [Icloud3 Device Tracker](https://github.com/gcobb321/icloud3)

_iCloud3, Version 2 - An advanced device tracker custom component for iPhones, iPads, etc. that monitors zone & location updates triggered by the HA iOS App_


[**My configuration for Icloud3 Device Tracker**](./packages/integrations/custom/icloud3.yaml)
**Version** | v2.4.7
--|--
**Author(s)** | @gcobb321

### [<img src="https://brands.home-assistant.io/_/emscrss/icon.png" height="24"/>](https://brands.home-assistant.io/_/emscrss/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/emscrss/icon.png" height="24"/>](https://brands.home-assistant.io/_/emscrss/icon.png#gh-light-mode-only) [Emsc Earthquake Rss Feed](https://github.com/msekoranja/emsc-hacs-repository)

_EMSC Home Assistant Integration_


[**My configuration for Emsc Earthquake Rss Feed**](./packages/integrations/custom/emscrss.yaml)
**Version** | None
--|--
**Author(s)** | @msekoranja

### [<img src="https://brands.home-assistant.io/_/auto_backup/icon.png" height="24"/>](https://brands.home-assistant.io/_/auto_backup/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/auto_backup/icon.png" height="24"/>](https://brands.home-assistant.io/_/auto_backup/icon.png#gh-light-mode-only) [Auto Backup](https://github.com/jcwillox/hass-auto-backup)

_🗃️ Improved Backup Service for Home Assistant that can Automatically Remove Backups and Supports Generational Backup Schemes._

**Version** | 1.3.1
--|--
**Author(s)** | @jcwillox

### [<img src="https://brands.home-assistant.io/_/anniversaries/icon.png" height="24"/>](https://brands.home-assistant.io/_/anniversaries/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/anniversaries/icon.png" height="24"/>](https://brands.home-assistant.io/_/anniversaries/icon.png#gh-light-mode-only) [Anniversaries](https://github.com/pinkywafer/Anniversaries)

_Anniversary Countdown Sensor for Home Assistant_

**Version** | 5.2.0
--|--
**Author(s)** | @pinkywafer

### [<img src="https://brands.home-assistant.io/_/blueiris/icon.png" height="24"/>](https://brands.home-assistant.io/_/blueiris/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/blueiris/icon.png" height="24"/>](https://brands.home-assistant.io/_/blueiris/icon.png#gh-light-mode-only) [Blueiris Nvr](https://github.com/elad-bar/ha-blueiris)

_Integration with Blue Iris Video Security Software_

**Version** | v1.0.15
--|--
**Author(s)** | @elad-bar, @kramttocs

### [<img src="https://brands.home-assistant.io/_/monitor_docker/icon.png" height="24"/>](https://brands.home-assistant.io/_/monitor_docker/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/monitor_docker/icon.png" height="24"/>](https://brands.home-assistant.io/_/monitor_docker/icon.png#gh-light-mode-only) [Monitor Docker](https://github.com/ualex73/monitor_docker)

_Monitor Docker containers from Home Assistant_


[**My configuration for Monitor Docker**](./packages/integrations/custom/monitor_docker.yaml)
**Version** | 1.14
--|--
**Author(s)** | @ualex73

### [<img src="https://brands.home-assistant.io/_/fedex/icon.png" height="24"/>](https://brands.home-assistant.io/_/fedex/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/fedex/icon.png" height="24"/>](https://brands.home-assistant.io/_/fedex/icon.png#gh-light-mode-only) [Fedex](https://github.com/custom-components/fedex)

_The fedex platform allows one to track deliveries by FedEx_


[**My configuration for Fedex**](./packages/integrations/custom/fedex.yaml)
**Version** | None
--|--

### [<img src="https://brands.home-assistant.io/_/meural/icon.png" height="24"/>](https://brands.home-assistant.io/_/meural/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/meural/icon.png" height="24"/>](https://brands.home-assistant.io/_/meural/icon.png#gh-light-mode-only) [Ha Meural](https://github.com/GuySie/ha-meural)

_Integration for NETGEAR Meural Canvas digital art frame in Home Assistant _

**Version** | v1.0.1
--|--
**Author(s)** | @guysie

### [<img src="https://brands.home-assistant.io/_/mail_and_packages/icon.png" height="24"/>](https://brands.home-assistant.io/_/mail_and_packages/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/mail_and_packages/icon.png" height="24"/>](https://brands.home-assistant.io/_/mail_and_packages/icon.png#gh-light-mode-only) [Mail And Packages](https://github.com/moralmunky/Home-Assistant-Mail-And-Packages)

_Home Assistant integration providing day of package counts and USPS informed delivery images._

**Version** | 0.3.10
--|--
**Author(s)** | @moralmunky, @firstof9

### [<img src="https://brands.home-assistant.io/_/couchpotato/icon.png" height="24"/>](https://brands.home-assistant.io/_/couchpotato/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/couchpotato/icon.png" height="24"/>](https://brands.home-assistant.io/_/couchpotato/icon.png#gh-light-mode-only) [Couchpotato](https://github.com/youdroid/home-assistant-couchpotato)

_🎥 CouchPotato component to feed Upcoming Media Card._


[**My configuration for Couchpotato**](./packages/integrations/custom/couchpotato.yaml)
**Version** | V1.2.2
--|--
**Author(s)** | @youdroid

### [<img src="https://brands.home-assistant.io/_/email/icon.png" height="24"/>](https://brands.home-assistant.io/_/email/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/email/icon.png" height="24"/>](https://brands.home-assistant.io/_/email/icon.png#gh-light-mode-only) [Email Sensor](https://github.com/ljmerza/ha-email-sensor)

_Email Sensor for collecting tracking numbers from over 30 providers._


[**My configuration for Email Sensor**](./packages/integrations/custom/email.yaml)
**Version** | 3.8.0
--|--
**Author(s)** | @ljmerza

### [<img src="https://brands.home-assistant.io/_/hpprinter/icon.png" height="24"/>](https://brands.home-assistant.io/_/hpprinter/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/hpprinter/icon.png" height="24"/>](https://brands.home-assistant.io/_/hpprinter/icon.png#gh-light-mode-only) [Hp Printers Integration](https://github.com/elad-bar/ha-hpprinter)

_HP Printer Integration_

**Version** | v1.0.8
--|--
**Author(s)** | @elad-bar

### [<img src="https://brands.home-assistant.io/_/pirateweather/icon.png" height="24"/>](https://brands.home-assistant.io/_/pirateweather/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/pirateweather/icon.png" height="24"/>](https://brands.home-assistant.io/_/pirateweather/icon.png#gh-light-mode-only) [Pirate Weather](https://github.com/alexander0042/pirate-weather-ha)

_Replacement for the default Dark Sky Home Assistant integration using Pirate Weather _

**Version** | v1.02
--|--
**Author(s)** | @alexander0042

### [<img src="https://brands.home-assistant.io/_/adaptive_lighting/icon.png" height="24"/>](https://brands.home-assistant.io/_/adaptive_lighting/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/adaptive_lighting/icon.png" height="24"/>](https://brands.home-assistant.io/_/adaptive_lighting/icon.png#gh-light-mode-only) [Adaptive Lighting](https://github.com/basnijholt/adaptive-lighting)

_Adaptive Lighting custom component for Home Assistant_

**Version** | 1.4.1
--|--
**Author(s)** | @basnijholt, @RubenKelevra

### [<img src="https://brands.home-assistant.io/_/cryptostate/icon.png" height="24"/>](https://brands.home-assistant.io/_/cryptostate/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/cryptostate/icon.png" height="24"/>](https://brands.home-assistant.io/_/cryptostate/icon.png#gh-light-mode-only) [Crypto Tracker](https://github.com/BigNocciolino/CryptoTracker)

_Integration for Home Assistant to implement a crypto tracking system_

**Version** | v2.0.2
--|--
**Author(s)** | @PepegaBruh

### [<img src="https://brands.home-assistant.io/_/thermal_comfort/icon.png" height="24"/>](https://brands.home-assistant.io/_/thermal_comfort/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/thermal_comfort/icon.png" height="24"/>](https://brands.home-assistant.io/_/thermal_comfort/icon.png#gh-light-mode-only) [Thermal Comfort](https://github.com/dolezsa/thermal_comfort)

_Thermal Comfort sensor for HA (absolute humidity, heat index, dew point, thermal perception)_

**Version** | 2.1.1
--|--
**Author(s)** | @dolezsa

### [<img src="https://brands.home-assistant.io/_/o365/icon.png" height="24"/>](https://brands.home-assistant.io/_/o365/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/o365/icon.png" height="24"/>](https://brands.home-assistant.io/_/o365/icon.png#gh-light-mode-only) [Office 365 Integration](https://github.com/RogerSelwyn/O365-HomeAssistant)

_Office 365 integration for Home Assistant_


[**My configuration for Office 365 Integration**](./packages/integrations/custom/o365.yaml)
**Version** | v4.2.8
--|--
**Author(s)** | @RogerSelwyn

### [<img src="https://brands.home-assistant.io/_/holidays/icon.png" height="24"/>](https://brands.home-assistant.io/_/holidays/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/holidays/icon.png" height="24"/>](https://brands.home-assistant.io/_/holidays/icon.png#gh-light-mode-only) [Holidays](https://github.com/bruxy70/Holidays)

_📅 Custom Home Assistant integration for public holidays - also used for garbage_collection integration to automatically move scheduled events that fall on a public holiday (by an automation blueprint)_

**Version** | 1.9.4
--|--
**Author(s)** | @bruxy70

### [<img src="https://brands.home-assistant.io/_/ics_calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/ics_calendar/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ics_calendar/icon.png" height="24"/>](https://brands.home-assistant.io/_/ics_calendar/icon.png#gh-light-mode-only) [Ics Calendar (Icalendar)](https://github.com/franc6/ics_calendar)

_Provides an ICS (icalendar) platform for the Home Assistant calendar_


[**My configuration for Ics Calendar (Icalendar)**](./packages/integrations/custom/ics_calendar.yaml)
**Version** | 3.1.7
--|--
**Author(s)** | @franc6

### [<img src="https://brands.home-assistant.io/_/hass_agent/icon.png" height="24"/>](https://brands.home-assistant.io/_/hass_agent/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/hass_agent/icon.png" height="24"/>](https://brands.home-assistant.io/_/hass_agent/icon.png#gh-light-mode-only) [Hass.Agent](https://github.com/LAB02-Research/HASS.Agent-Integration)

_HASS.Agent's Home Assistant integration. Adds notifications and mediaplayer capabilities to HASS.Agent - a Windows based client (companion app) for Home Assistant._

**Version** | v2022.11.9
--|--
**Author(s)** | @fillefilip8, @LAB02-Admin

### [<img src="https://brands.home-assistant.io/_/uptime_kuma/icon.png" height="24"/>](https://brands.home-assistant.io/_/uptime_kuma/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/uptime_kuma/icon.png" height="24"/>](https://brands.home-assistant.io/_/uptime_kuma/icon.png#gh-light-mode-only) [Uptime Kuma](https://github.com/meichthys/uptime_kuma)

_Uptime Kuma HACS integration_

**Version** | v2.1.1
--|--
**Author(s)** | @meichthys, @jayakornk

### [<img src="https://brands.home-assistant.io/_/nest_protect/icon.png" height="24"/>](https://brands.home-assistant.io/_/nest_protect/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/nest_protect/icon.png" height="24"/>](https://brands.home-assistant.io/_/nest_protect/icon.png#gh-light-mode-only) [Nest Protect](https://github.com/nicoinch/ha-nest-protect)

_Nest Protect integration for Home Assistant. This will allow you to integrate your smoke, heat, co and occupancy status real-time in HA._

**Version** | None
--|--
**Author(s)** | @imicknl

### [<img src="https://brands.home-assistant.io/_/esxi_stats/icon.png" height="24"/>](https://brands.home-assistant.io/_/esxi_stats/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/esxi_stats/icon.png" height="24"/>](https://brands.home-assistant.io/_/esxi_stats/icon.png#gh-light-mode-only) [Esxi Stats](https://github.com/wxt9861/esxi_stats)

_ESXi component for Home Assistant_

**Version** | 0.6.4
--|--
**Author(s)** | @wxt9861

### [<img src="https://brands.home-assistant.io/_/asterisk/icon.png" height="24"/>](https://brands.home-assistant.io/_/asterisk/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/asterisk/icon.png" height="24"/>](https://brands.home-assistant.io/_/asterisk/icon.png#gh-light-mode-only) [Asterisk Hass Integration](https://github.com/TECH7Fox/asterisk-hass-integration)

_Asterisk integration for Home Assistant_

**Version** | v0.9.8
--|--
**Author(s)** | @TECH7Fox

### [<img src="https://brands.home-assistant.io/_/hdhomerun/icon.png" height="24"/>](https://brands.home-assistant.io/_/hdhomerun/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/hdhomerun/icon.png" height="24"/>](https://brands.home-assistant.io/_/hdhomerun/icon.png#gh-light-mode-only) [Hdhomerun](https://github.com/uvjim/hass_hdhomerun)

_Home Assistant integration for HDHomeRun_

**Version** | 2022.11.1
--|--
**Author(s)** | @uvjim

### [<img src="https://brands.home-assistant.io/_/opnsense/icon.png" height="24"/>](https://brands.home-assistant.io/_/opnsense/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/opnsense/icon.png" height="24"/>](https://brands.home-assistant.io/_/opnsense/icon.png#gh-light-mode-only) [Opnsense Integration For Home Assistant](https://github.com/travisghansen/hass-opnsense)

_OPNsense integration with Home Assistant_

**Version** | v0.1.14
--|--
**Author(s)** | @travisghansen

### [<img src="https://brands.home-assistant.io/_/ha_skyfield/icon.png" height="24"/>](https://brands.home-assistant.io/_/ha_skyfield/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ha_skyfield/icon.png" height="24"/>](https://brands.home-assistant.io/_/ha_skyfield/icon.png#gh-light-mode-only) [Skyfield Panel With Sun, Moon, And Planets](https://github.com/partofthething/ha_skyfield)

_See the apparent positions of the Sun, Moon, and planets in this home assistant custom component_


[**My configuration for Skyfield Panel With Sun, Moon, And Planets**](./packages/integrations/custom/ha_skyfield.yaml)
**Version** | None
--|--

### [<img src="https://brands.home-assistant.io/_/noaa_space_weather/icon.png" height="24"/>](https://brands.home-assistant.io/_/noaa_space_weather/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/noaa_space_weather/icon.png" height="24"/>](https://brands.home-assistant.io/_/noaa_space_weather/icon.png#gh-light-mode-only) [Noaa Space Weather](https://github.com/tcarwash/home-assistant_noaa-space-weather)

_A home assistant custom component to integrate with the NOAA Space Weather Prediction Center API_

**Version** | v1.1.0
--|--
**Author(s)** | @tcarwash

### [<img src="https://brands.home-assistant.io/_/ham_radio_propagation/icon.png" height="24"/>](https://brands.home-assistant.io/_/ham_radio_propagation/dark_icon.png#gh-dark-mode-only)[<img src="https://brands.home-assistant.io/_/ham_radio_propagation/icon.png" height="24"/>](https://brands.home-assistant.io/_/ham_radio_propagation/icon.png#gh-light-mode-only) [Ham Radio Propagation](https://github.com/emics/ham_radio_propagation)

_Custom component for Home Assistant that integrates HAM Radio Propagation information._


[**My configuration for Ham Radio Propagation**](./packages/integrations/custom/ham_radio_propagation.yaml)
**Version** | v0.1.5
--|--

## The custom lovelace plugins that I use

###  [Flexible Horseshoe Card For Lovelace](https://github.com/AmoebeLabs/flex-horseshoe-card)

_Flexible Horseshoe card for Home Assistant Lovelace UI. A card with a flexible layout,  a horseshoe-like donut graph, multiple entities or attributes, graphics and animations!_

**Version** | 0.9.0
--|--

###  [Mini Climate Card](https://github.com/artem-sedykh/mini-climate-card)

_Minimalistic climate card for Home Assistant Lovelace UI_

**Version** | v2.4.4
--|--

###  [Zigbee2Mqtt Networkmap Card](https://github.com/azuwis/zigbee2mqtt-networkmap)

_Home Assistant Custom Card to show Zigbee2mqtt network map_

**Version** | v0.7.0
--|--

###  [Github Entity Row](https://github.com/benct/lovelace-github-entity-row)

_GitHub repository sensor data on entity rows in Home Assistant's Lovelace UI_

**Version** | v2.1.0
--|--

###  [Weather Card](https://github.com/bramkragten/weather-card)

_Weather Card with animated icons for Home Assistant Lovelace_

**Version** | v1.5.0
--|--

###  [Multiple Entity Row](https://github.com/benct/lovelace-multiple-entity-row)

_Show multiple entity states and attributes on entity rows in Home Assistant's Lovelace UI_

**Version** | v4.4.1
--|--

###  [Swipe Card](https://github.com/bramkragten/swipe-card)

_Card that allows you to swipe throught multiple cards for Home Assistant Lovelace_

**Version** | v5.0.0
--|--

###  [Bar Card](https://github.com/custom-cards/bar-card)

_Customizable Animated Bar card for Home Assistant Lovelace_

**Version** | 3.2.0
--|--

###  [Button Card](https://github.com/custom-cards/button-card)

_❇️ Lovelace button-card for home assistant_

**Version** | v3.4.2
--|--

###  [Circle Sensor Card](https://github.com/custom-cards/circle-sensor-card)

_A custom component for displaying sensor values as cards or elements_

**Version** | 1.2.2
--|--

###  [Entity Attributes Card](https://github.com/custom-cards/entity-attributes-card)

_Entity Attributes_

**Version** | 0.1.2
--|--

###  [Decluttering Card](https://github.com/custom-cards/decluttering-card)

_🧹 Declutter your lovelace configuration with the help of this card_

**Version** | 0.6.3
--|--

###  [Flex Table   Highly Customizable, Data Visualization](https://github.com/custom-cards/flex-table-card)

_Highly Flexible Lovelace Card - arbitrary contents/columns/rows, regex matched, perfect to show appdaemon created content and anything breaking out of the entity_id + attributes concept_

**Version** | v0.7.2
--|--

###  [Spotify Lovelace Card](https://github.com/custom-cards/spotify-card)

_Spotify playlist card for Home Assistant card_

**Version** | v2.4.0
--|--

###  [Stack In Card](https://github.com/custom-cards/stack-in-card)

_🛠 group multiple cards into one card without the borders_

**Version** | 0.2.0
--|--

###  [Vacuum Card](https://github.com/denysdovhan/vacuum-card)

_Vacuum cleaner card for Home Assistant Lovelace UI_

**Version** | v2.6.3
--|--

###  [Ha Floorplan](https://github.com/ExperienceLovelace/ha-floorplan)

_Bring new life to Home Assistant. By mapping entities to a SVG-object, you're able to control devices, show states, calling services - and much more. Add custom styling on top, to visualize whatever you can think of. Your imagination just become the new limit._

**Version** | 1.0.35
--|--

###  [Lovelace Card Templater](https://github.com/gadgetchnnel/lovelace-card-templater)

_Custom Lovelace card which allows Jinja2 templates to be applied to other cards_

**Version** | 0.0.17
--|--

###  [Config Template Card](https://github.com/iantrich/config-template-card)

_📝 Templatable Lovelace Configurations_

**Version** | 1.3.6
--|--

###  [Podcast Card](https://github.com/iantrich/podcast-card)

_🎧 Podcast Player Card_

**Version** | 1.0.9
--|--

###  [Restriction Card](https://github.com/iantrich/restriction-card)

_🔒 Apply restrictions to Lovelace cards_

**Version** | 1.2.7
--|--

###  [Text Divider Row](https://github.com/iantrich/text-divider-row)

_🗂 Text Divider Row_

**Version** | 1.4.1
--|--

###  [Canary](https://github.com/jcwillox/lovelace-canary)

_🐤 Adds many useful extensions to lovelace, such as templating secondary info, stacking within a card and more!_

**Version** | 0.4.0
--|--

###  [Simple Weather Card](https://github.com/kalkih/simple-weather-card)

_Minimalistic weather card for Home Assistant_

**Version** | v0.8.3
--|--

###  [Mini Graph Card](https://github.com/kalkih/mini-graph-card)

_Minimalistic graph card for Home Assistant Lovelace UI_

**Version** | v0.11.0
--|--

###  [Lovelace Html Card](https://github.com/PiotrMachowski/lovelace-html-card)

_This card displays provided data as an HTML content of a card._

**Version** | v1.0.0
--|--

###  [Ha (Lovelace) Card Weather Conditions](https://github.com/r-renato/ha-card-weather-conditions)

_Weather condition card (Lovelace) for Home Assistant._

**Version** | 1.9.13
--|--

###  [Harmony Card](https://github.com/sbryfcz/harmony-card)

_A Home Assistant Lovelace Care for Harmony Integration_

**Version** | v0.14.1
--|--

###  [Honeycomb Menu](https://github.com/Sian-Lee-SA/honeycomb-menu)

_Honeycomb menu is a Home Assistant module (not a card) that can be applied to any lovelace card. When activated by the defined action on said card, the module will display a 'rounded' list of honeycomb buttons with an optional XY pad to make interfacing with lovelace more fluent_

**Version** | 0.11.0
--|--

###  [Lovelace Media Art Background](https://github.com/TheLastProject/lovelace-media-art-background)

_Sets the background of your Home Assistant to match the entity picture of a media player_

**Version** | None
--|--

###  [Card Mod](https://github.com/thomasloven/lovelace-card-mod)

_🔹 Add CSS styles to (almost) any lovelace card_

**Version** | 3.2.0
--|--

###  [Fold Entity Row](https://github.com/thomasloven/lovelace-fold-entity-row)

_🔹 A foldable row for entities card, containing other rows_

**Version** | 2.2.0
--|--

###  [Hui Element](https://github.com/thomasloven/lovelace-hui-element)

_🔹 Use built-in elements in the wrong place_

**Version** | None
--|--

###  [More Info Card](https://github.com/thomasloven/lovelace-more-info-card)

_🔹 Display the more-info dialog of any entity as a lovelace card_

**Version** | None
--|--

###  [Layout Card](https://github.com/thomasloven/lovelace-layout-card)

_🔹 Get more control over the placement of lovelace cards._

**Version** | 2.4.4
--|--

###  [Slider Entity Row](https://github.com/thomasloven/lovelace-slider-entity-row)

_🔹 Add sliders to entity cards_

**Version** | 17.3.0
--|--

###  [State Switch](https://github.com/thomasloven/lovelace-state-switch)

_🔹Dynamically replace lovelace cards depending on occasion_

**Version** | 1.9.5
--|--

###  [Template Entity Row](https://github.com/thomasloven/lovelace-template-entity-row)

_🔹 Display whatever you want in an entities card row._

**Version** | 1.3.0
--|--

###  [Lovelace Animated Background](https://github.com/Villhellm/lovelace-animated-background)

_Animated backgrounds for lovelace _

**Version** | v0.6.3
--|--

###  [Bha Icon Pack](https://github.com/hulkhaugen/hass-bha-icons)

_Additional icons for Home Assistant to accompany the MDI icons_

**Version** | None
--|--

###  [Apexcharts Card](https://github.com/RomRider/apexcharts-card)

_📈 A Lovelace card to display advanced graphs and charts based on ApexChartsJS for Home Assistant_

**Version** | v2.0.2
--|--

###  [Uptime Card](https://github.com/dylandoamaral/uptime-card)

_Minimalistic uptime card for Home Assistant Lovelace UI_

**Version** | v0.14.0
--|--

###  [Notify Card](https://github.com/bernikr/lovelace-notify-card)

_Send notifications directly from the dashboard_

**Version** | None
--|--

###  [Fan Percent Button Row](https://github.com/finity69x2/fan-percent-button-row)

_Frontend plugin to control fans in Home Assistant using percent values for speeds_

**Version** | 2.0
--|--

###  [Multiline Entity Card](https://github.com/jampez77/Multiline-Entity-Card)

_A custom entity card for Home Assistant that allows text to span multiple lines._

**Version** | 1.2.2
--|--

###  [Kodi Search Card](https://github.com/jtbgroup/kodi-search-card)

_Custom card for home assistant allowing to search in the libraries of kodi_

**Version** | 3.4.3
--|--

###  [Knx User Forum Icon Set](https://github.com/mampfes/ha-knx-uf-iconset)

_Icon set from KNX User Forum for Home Assistant. The icon set contains more than 900 icons for home automation._

**Version** | 1.1.0
--|--

###  [Custom Brand Icons](https://github.com/elax46/custom-brand-icons)

_Custom brand icons for Home Assistant_

**Version** | 2023.3.2
--|--

###  [Sun Card](https://github.com/AitorDB/home-assistant-sun-card)

_Home assistant sun card based on Google weather design_

**Version** | v0.1.4
--|--

###  [Timer Bar Card](https://github.com/rianadon/timer-bar-card)

_A progress bar display for Home Assistant timers_

**Version** | v1.26
--|--

###  [Battery Entity Row](https://github.com/benct/lovelace-battery-entity-row)

_Show battery states or attributes with dynamic icon on entity rows in Home Assistant's Lovelace UI_

**Version** | v1.3.1
--|--

###  [Secondaryinfo Entity Row](https://github.com/custom-cards/secondaryinfo-entity-row)

_Custom entity row for HomeAssistant, providing additional types of data to be displayed in the secondary info area of the Lovelace Entities card_

**Version** | 5.0
--|--

###  [Rpi Monitor Card](https://github.com/ironsheep/lovelace-rpi-monitor-card)

_A Raspberry Pi status display Card for Home Assistant Lovelace_

**Version** | v1.4.2
--|--

###  [Card Tools](https://github.com/thomasloven/lovelace-card-tools)

_🔹A collection of tools for other lovelace plugins to use_

**Version** | 11
--|--

###  [Power Distribution Card](https://github.com/JonahKr/power-distribution-card)

_A Lovelace Card for visualizing power distributions._

**Version** | v2.5.9
--|--

###  [Mini Media Player](https://github.com/kalkih/mini-media-player)

_Minimalistic media card for Home Assistant Lovelace UI_

**Version** | v1.16.5
--|--

###  [Ha (Lovelace) Card Waze Travel Time](https://github.com/r-renato/ha-card-waze-travel-time)

_Home Assistant Lovelace card for Waze Travel Time Sensor_

**Version** | None
--|--

###  [Power Wheel Card](https://github.com/gurbyz/power-wheel-card)

_An intuitive way to represent the power and energy that your home is consuming or producing. (A custom card for the Lovelace UI of Home Assistant.)_

**Version** | v0.1.5
--|--

###  [Kodi Playlist Card](https://github.com/jtbgroup/kodi-playlist-card)

_This repository is used to contain the code of a kodi playlist card for Home Assistant and publish it via HACS_

**Version** | 4.4.2
--|--

###  [Tempometer Gauge Card](https://github.com/SNoof85/lovelace-tempometer-gauge-card-deprecated)

_Home Assistant Lovelace custom card with Barometer, Thermomer themes and customs themes as well !_

**Version** | 1.40
--|--

###  [Vertical Stack In Card](https://github.com/ofekashery/vertical-stack-in-card)

_📐 Home Assistant Card: Group multiple cards into a single sleek card._

**Version** | v0.4.4
--|--

###  [Custom Sidebar](https://github.com/Villhellm/custom-sidebar)

_Custom Sidebar for Home Assistant_

**Version** | v0.2.2
--|--

###  [Lovelace Grocy Chores Card](https://github.com/isabellaalstrom/lovelace-grocy-chores-card)

_A card to track chores and tasks in Grocy._

**Version** | v3.5.1
--|--

###  [Air Visual Card](https://github.com/dnguyen800/air-visual-card)

_A Lovelace card showing air quality data from airvisual.com. Requires the AirVisual component._

**Version** | 2.0.2
--|--

###  [Garbage Collection Card](https://github.com/amaximus/garbage-collection-card)

_Custom Lovelace card for Garbage Collection custom component_

**Version** | 1.23.3
--|--

###  [Rgb Light Card](https://github.com/bokub/rgb-light-card)

_💡 A Lovelace custom card for RGB lights_

**Version** | 1.11.0
--|--

###  [Logbook Card](https://github.com/royto/logbook-card)

_Logbook card for Home Assistant UI Lovelace_

**Version** | 1.9.3
--|--

###  [Lovelace Home Feed Card](https://github.com/gadgetchnnel/lovelace-home-feed-card)

_A custom Lovelace card for displaying a combination of persistent notifications, calendar events, and entities in the style of a feed._

**Version** | 0.6.3
--|--

###  [Dual Gauge Card](https://github.com/custom-cards/dual-gauge-card)

_Dual gauge custom card for Lovelace in Home Assistant_

**Version** | 0.5.3
--|--

###  [Auto Entities](https://github.com/thomasloven/lovelace-auto-entities)

_🔹Automatically populate the entities-list of lovelace cards_

**Version** | 1.12.1
--|--

###  [Scheduler Card](https://github.com/nielsfaber/scheduler-card)

_HA Lovelace card for control of scheduler entities_

**Version** | v3.2.8
--|--

###  [Dark Thermostat](https://github.com/ciotlosm/lovelace-thermostat-dark-card)

_🌡 Thermostat card with a round and black feel to it_

**Version** | 0.0.5
--|--

###  [Update Time Card](https://github.com/itobey/update-time-card)

_Simple last-updated card for Home assistant lovelace_

**Version** | 2.0.0
--|--

###  [Hass Hue Icons](https://github.com/arallsopp/hass-hue-icons)

_Additional vector icons for home assistant to model Philips  Hue bulbs and fixtures. _

**Version** | v1.2.51
--|--

###  [Atomic Calendar Revive](https://github.com/totaldebug/atomic-calendar-revive)

_An advanced calendar card for Home Assistant Lovelace._

**Version** | v7.2.0
--|--

###  [History Explorer Card](https://github.com/alexarch21/history-explorer-card)

_A card for Home Assistant Lovelace for exploring the history of your entities interactively and in real time._

**Version** | v1.0.44
--|--

###  [Plotly Graph Card](https://github.com/dbuezas/lovelace-plotly-graph-card)

_Highly customisable Lovelace card to plot interactive graphs. Brings scrolling, zooming, and much more!_

**Version** | v3.3.1
--|--

###  [Fluid Level Background Card](https://github.com/swingerman/lovelace-fluid-level-background-card)

_This card wraps any other cards and renders a fluid background behind them._

**Version** | v0.1.2
--|--

###  [Thermal Comfort Icons](https://github.com/rautesamtr/thermal_comfort_icons)

_Thermal Comfort custom icons for Home Assistant to accompany the MDI icons_

**Version** | 1.3.0
--|--

###  [Sonos Card](https://github.com/johanfrick/custom-sonos-card)

_Home Assistant custom lovelace sonos card_

**Version** | v5.20.1
--|--

###  [Mushroom](https://github.com/piitaya/lovelace-mushroom)

_Mushroom Cards - Build a beautiful dashboard easily 🍄_

**Version** | v2.6.1
--|--

###  [Only Lock Lock Row](https://github.com/frozenwizard/onlylocklock)

_Custom entity rows that prevent users from unlocking a lock, disarming a security system(alarm), opening a cover(garage door)._

**Version** | v0.5
--|--

###  [Minimalistic Area Card](https://github.com/junalmeida/homeassistant-minimalistic-area-card)

_A minimalistic area card with sensors and buttons._

**Version** | v1.1.8
--|--

###  [Weather Radar Card](https://github.com/Makin-Things/weather-radar-card)

_A rain radar card using the tiled images from RainViewer_

**Version** | v2.1.0
--|--

###  [Power Flow Card](https://github.com/ulic75/power-flow-card)

_A power distribution card inspired by the official Energy Distribution card for Home Assistant_

**Version** | v2.6.2
--|--

###  [Sankey Chart Card](https://github.com/MindFreeze/ha-sankey-chart)

_A Home Assistant lovelace card to display a sankey chart. For example for power consumption_

**Version** | v1.11.0
--|--

###  [Custom Icons](https://github.com/Mariusthvdb/custom-icons)

_Several custom made and legacy icons, and icons collected all over the internet in 1 set, UI selectable._

**Version** | v0.3.7
--|--

###  [Datetime Card](https://github.com/a-p-z/datetime-card)

_A minimalistic card for Home Assistant Lovelace UI which shows how many days it has been between any input_datetime and today._

**Version** | v1.0.2
--|--

###  [Home Assistant Swipe Navigation](https://github.com/zanna-37/hass-swipe-navigation)

_↔️ Swipe through Home Assistant Dashboard views on mobile._

**Version** | v1.11.0
--|--

###  [Hue Like Light Card](https://github.com/Gh61/lovelace-hue-like-light-card)

_This card provides a Hue-like way to control your lights in Home Assistant._

**Version** | v1.3.0
--|--

###  [Upcoming Media Card](https://github.com/NemesisRE/upcoming-media-card)

_📺 A card to display upcoming episodes and movies from services like: Plex, Kodi, Radarr, Sonarr, and Trakt._

**Version** | 0.4.4
--|--

###  [Kiosk Mode](https://github.com/NemesisRE/kiosk-mode)

_🙈 Hides the Home Assistant header and/or sidebar_

**Version** | 1.7.8
--|--

###  [Hourly Weather Card](https://github.com/decompil3d/lovelace-hourly-weather)

_Hourly weather card for Home Assistant. Visualize upcoming weather conditions as a colored horizontal bar._

**Version** | 4.10.1
--|--

###  [Slider Button Card](https://github.com/custom-cards/slider-button-card)

_A button card with integrated slider_

**Version** | v1.10.10
--|--

###  [Platinum Weather Card](https://github.com/Makin-Things/platinum-weather-card)

_This is a fully customisable weather card for Home Assistant with a graphical configuration._

**Version** | 1.0.5
--|--

###  [Tv Remote Card (With Touchpad And Haptic Feedback)](https://github.com/usernein/tv-card)

_📺 TV Remote Card (with touchpad and haptic feedback)_

**Version** | v0.5.2
--|--

###  [Swiss Army Knife Custom Card](https://github.com/AmoebeLabs/swiss-army-knife-card)

_The versatile custom Swiss Army Knife card for Home Assistant allows you to create your unique visualization using several graphical tools, styling options and animations._

**Version** | v1.0.0-rc.3
--|--

###  [Room Card](https://github.com/marcokreeft87/room-card)

_Show multiple entity states, attributes and icons in a single card in Home Assistant's Lovelace UI_

**Version** | 1.07.11
--|--

###  [Tabbed Card](https://github.com/kinghat/tabbed-card)

_a custom card for home assistant that utilizes tabs to segregate individual cards._

**Version** | v0.3.1
--|--

###  [Clock Weather Card](https://github.com/pkissling/clock-weather-card)

_A Home Assistant Card indicating today's date/time, along with an iOS inspired weather forecast for the next days with animated icons_

**Version** | 1.0.12
--|--

###  [Daily Schedule Card](https://github.com/amitfin/lovelace-daily-schedule-card)

_Home Assistant Custom Card for Daily Schedule Integration_

**Version** | v1.1.1
--|--

###  [Ultimate Tv Remote Card With Touchpad And More](https://github.com/iablon/HomeAssistant-Touchpad-Card)

_A card that simplifies TV interaction from HomeAssistant_

**Version** | fix-more-functions
--|--

###  [Formula One Card](https://github.com/marcokreeft87/formulaone-card)

_Present the data of Formula One in a pretty way_

**Version** | 1.2.1
--|--

###  [Vpd Chart Card](https://github.com/vpdchart/vpdchart-card)

_A VPD chart card for Home Assistant_

**Version** | v1.0.0
--|--

###  [Sip Card](https://github.com/TECH7Fox/sip-hass-card)

_A SIP client inside home assistant!_

**Version** | v2.4.0
--|--

###  [Energy Overview Card](https://github.com/Sese-Schneider/ha-energy-overview-card)

_A simple card which displays energy usage details of one or multiple entities._

**Version** | v2.4.2
--|--

###  [Big Slider Card](https://github.com/nicufarmache/lovelace-big-slider-card)

_A card with a big slider for light entities in Home Assistant_

**Version** | 1.0.8
--|--

###  [Lovelace Theme Maker](https://github.com/thomasloven/lovelace-theme-maker)

_None_

**Version** | None
--|--

###  [List Card](https://github.com/iantrich/list-card)

_📰 Display sensor list data in a table_

**Version** | 0.1.2
--|--

###  [Astroweather Card](https://github.com/mawinkler/astroweather-card)

_Lovalace Card for the AstroWeather Integration_

**Version** | v0.22.2
--|--

###  [Weather Chart Card](https://github.com/Yevgenium/weather-chart-card)

_Custom weather card with charts_

**Version** | 1.2.0
--|--

## The custom themes that I use

###  [Google Dark Theme](https://github.com/pacjo/google_dark_animated)

_A fork of popular Home Assistant Google dark theme with animated icons_

**Version** | v1.9
--|--

###  [Material 3 Dark & Light Theme 07: Darkolivegreen](https://github.com/AmoebeLabs/HA-Theme_M3-07-DarkOliveGreen)

_Material Design 3 based theme (dark olive green) for Home Assistant_

**Version** | v1.1.2
--|--

###  [Ios Theme   Based On The System Wide Light And Dark Mode Ui](https://github.com/JuanMTech/ios-theme)

_🎨 By JuanMTech -- Theme based on the iOS system-wide light and dark mode interface_

**Version** | v.14
--|--

###  [Material 3 Dark & Light Theme 04: Magenta](https://github.com/AmoebeLabs/HA-Theme_M3-04-Magenta)

_Material Design 3 / Material YOU theme for Home Assistant_

**Version** | v1.1.2
--|--

###  [Mushroom Themes](https://github.com/piitaya/lovelace-mushroom-themes)

_Additional themes for Lovelace Mushroom Cards 🍄_

**Version** | v0.0.9
--|--

###  [Metrology   Metro + Fluent + Windows Themes   By Mmak.Es](https://github.com/Madelena/Metrology-for-Hass)

_🎨 Give your Home Assistant a modern and clean facelift. 🟥🟧🟩🟦🟪 24 Variations with 2 Styles + 6 Colors (Magenta Red / Orange / Green / Blue / Purple) + 🌞 Light and 🌚 Dark modes included. Based on Metro and Fluent UI Design Systems from Microsoft Windows._

**Version** | v.1.9.1
--|--

###  [Graphite Theme](https://github.com/TilmanGriesel/graphite)

_Calm and clean dark theme for Home Assistant_

**Version** | 2.1
--|--


***

Like all other Home Assistant instances this is also a Work in Progress :D

<!-- Footnotes -->
[^1]: UI Configuration
