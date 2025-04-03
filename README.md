
# Bearstorm Training Timer

Intervalový časovač pre tréningy. Nastavte dĺžku práce, oddychu a počet kôl. Komunikuje cez MQTT.

## Inštalácia cez HACS
1. Pridajte tento repozitár ako **Plugin**
2. Inštalujte `bearstorm-training-timer-hacs`
3. Pridajte do `resources`:
```yaml
- url: /hacsfiles/bearstorm-training-timer-hacs/bearstorm-timer.js
  type: module
```
4. Použite v Lovelace:
```html
<bearstorm-timer></bearstorm-timer>
```

## Licencia
Copyright Bearstorm.
