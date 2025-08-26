![VDS 278](https://github.com/user-attachments/assets/80d2bffa-ec2d-4f6f-91be-9bc244e9fa63)

# VDA 277 und VDA 278

## Unterstützte Standards
- **VDA 277** – Bestimmung der Emission flüchtiger organischer Verbindungen (VOC) aus Fahrzeugbauteilen. [Standardquelle](https://webshop.vda.de/de/vda-277)
- **VDA 278** – "Thermal Desorption Analysis of Organic Emissions for the Characterization of Non-Metallic Materials for Automobiles". [Standardquelle](https://webshop.vda.de/VDA/de/vda-278-05-2016) — Version: 1.0.0

## Nutzung
Zur Validierung eines Testberichts gegen das passende Schema kann das Python-Modul `jsonschema` verwendet werden:

```bash
pip install jsonschema
# VDA 278
python -m jsonschema -i VDA_231-301_Example_VDA_278.json VDA_231-301_Schema_VDA_278.json

# VDA 277 (analog, Dateien sind nicht im Repository enthalten)
python -m jsonschema -i <VDA277_Beispiel>.json <VDA277_Schema>.json
```

Ersetze die Dateinamen im zweiten Befehl durch die jeweiligen Dateien, wenn ein Schema für VDA 277 vorliegt.

## Dateien
| Standard | Schema | Beispiel |
|----------|--------|----------|
| VDA 277 | – | – |
| VDA 278 | [VDA_231-301_Schema_VDA_278.json](./VDA_231-301_Schema_VDA_278.json) | [VDA_231-301_Example_VDA_278.json](./VDA_231-301_Example_VDA_278.json) |

