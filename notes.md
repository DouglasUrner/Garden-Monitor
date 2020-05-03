## Spec

* Solar powered
* Sensors
   - Battery voltage
   - Light (solar energy - use solar panel to measure? Apparently the short circuit current of a solar panel is proportional to the energy input (presumably factored by the efficiency of the panel))
   - Soil Temperature x 4 (DS18B20)
   - Soil Humidity (VWC) x 4 (Vegetronix VH400)
   - Air Temperature & Humidity
* Web status / configuration
* Log data (JSON to server?)
   - Prometheus (https://github.com/prometheus/prometheus)
   - Grafana (https://github.com/grafana/grafana)
* Wakeup button / reporting LED
* Watchdog

## Hardware

### Raspberry Pi 0W

### ESP32

### ESP8266

## Power Management

* [Feather HUZZAH ESP8266 – Realistic Power Consumption](http://hex.ro/wp/blog/feather-huzzah-esp8266-realistic-power-consumption/)
* [ESP32 Power Management](https://learn.adafruit.com/adafruit-huzzah32-esp32-feather/power-management)
