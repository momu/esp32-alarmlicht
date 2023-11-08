# ESP32 Alarmlicht

[[_TOC_]]

Automatisierte Alarmauslösung über einen HTTP-Requests bei Alarmierung eines Melders in einer LGRA Ladestation.

Um eine automatisierte Alarmauslösung zu realisieren (z.B. über [DIVERA 24/7](https://www.divera247.com)), wird der Relaiskontakt 
des Swissphone Ladegeräts LGRA Expert

## Bill Of Materials

* [ESP32-EVB-EA-IND](https://www.olimex.com/Products/IoT/ESP32/ESP32-EVB)
* [BOX-ESP32-EVB-EA](https://www.olimex.com/Products/IoT/ESP32/BOX-ESP32-EVB-EA)


## Setup

```
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
esphome wizard alarmlicht.yaml
esphome run alarmlicht.yaml
```

## Lizenz

  <p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/momu/esp32-alarmlicht/">ESP32-Alarmlicht</a> is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p> 