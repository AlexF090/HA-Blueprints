# HA-Blueprints (Deutsch)

## Ziel

Home Assistant Blueprints, die du in deine Instanz importieren und wiederverwenden kannst.

## Enthaltene Blueprints

- `EnOcean PTM 215Z - Z2M 2.x (MQTT Device Trigger) v2` (DE)
  - Datei: `blueprints/automation/enocean_ptm215z_z2m_de.yaml`

[![Blueprint import (DE)](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2FAlexF090%2FHA-Blueprints%2Frefs%2Fheads%2Fmain%2Fblueprints%2Fautomation%2Fenocean_ptm215z_z2m_de.yaml)

## In Home Assistant importieren

1. Oeffne Home Assistant.
2. Gehe zu `Einstellungen` -> `Automationen & Szenen` -> `Blueprints`.
3. Klicke `Add Blueprint`.
4. Waehe `Import blueprint` / `Paste YAML` (je nach UI).
5. Fuege den Inhalt von `blueprints/automation/enocean_ptm215z_z2m_de.yaml` ein und klicke danach den Button `Import Blueprint to My Home Assistant`, um den Blueprint hinzuzufuegen.
6. Erstelle danach die Automation ueber den Blueprint (`Create Automation`) und fuelle die erforderlichen Inputs aus.

## Voraussetzungen (wichtig vor Erstellung/Activation)

Bevor du den Blueprint als Automation erstellst oder aktivierst:
- Druecke jede PTM215Z-Taste (1-4) einmal manuell.
- Damit registriert Z2M die Tasten als `MQTT Device Triggers` in Home Assistant.
- Stelle sicher, dass `MQTT Discovery` in deiner Z2M-Konfiguration aktiv ist (Standard).

## Community-Import ueber URL (optional)

Wenn du dieses Repo oeffentlich hostest (z.B. GitHub), kannst du per `Add Blueprint` auch ueber eine Raw-URL importieren:

`https://raw.githubusercontent.com/<user>/<repo>/main/blueprints/automation/enocean_ptm215z_z2m_de.yaml`

Danach klicke auf den Button `Import Blueprint to My Home Assistant`, um den Blueprint hinzuzufuegen.

