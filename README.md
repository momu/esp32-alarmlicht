# esp32-remote-alarmlicht

Auslösen eines HTTP-Requests bei Alarmierung eines Melders in einer LGRA Ladestation.


## Setup

```
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
esphome wizard alarmlicht.yaml
esphome run alarmlicht.yaml
```