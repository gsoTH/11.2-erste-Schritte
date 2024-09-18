# 11.2 erste Schritte
Entwickeln Sie Tests für die Funktionen in `mein_modul.py`!

Ziel: C0, C1- Abdeckung von 100%

## Tools
### pytest
Testtool für python

Installation: `pip install pytest`
 
Aufruf:
```python
pytest
pytest –verbose

#PATH-Fehler? (pytest unbekannt):
python –m pytest
```

### coverage
Analysiert die Testabdeckung
Installation:	pip install coverage

Aufruf: 
```python
coverage run -m pytest
coverage run --branch -m pytest
# anschließend:
coverage report oder:
coverage html
```
