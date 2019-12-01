# localtuya_thermostat
Local control from Home Assistant for tuya based thermostats

```yaml
- platform: localtuya
  host: Thermostat IP
  local_key: 'your local key'
  device_id: 'your device id'
  name: 'moes'
  scan_interval: 5
  min_temp: 5
  max_temp: 35
  protocol_version: 3.3
```
