# HA-Blueprints (English)

## Goal

Home Assistant Blueprints that you can import into your instance and reuse.

## Included Blueprints

- `EnOcean PTM 215Z - Z2M 2.x (MQTT Device Trigger) v2` (EN)
  - File: `blueprints/automation/enocean_ptm215z_z2m.yaml`

[![Import Blueprint to My Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2FAlexF090%2FHA-Blueprints%2Frefs%2Fheads%2Fmain%2Fblueprints%2Fautomation%2Fenocean_ptm215z_z2m.yaml)

## Import in Home Assistant

1. Open Home Assistant.
2. Go to `Settings` -> `Automations & Scenes` -> `Blueprints`.
3. Click `Add Blueprint`.
4. Choose `Import blueprint` / `Paste YAML` (depending on the UI).
5. Paste the content from `blueprints/automation/enocean_ptm215z_z2m.yaml` and click the button `Import Blueprint to My Home Assistant` to add the blueprint.
6. Create the automation from the blueprint (`Create Automation`) and fill in the required inputs.

## Prerequisites (important before creating/enabling)

Before you create or enable the automation:
- Press each PTM215Z button (1-4) once manually.
- This allows Z2M to register the buttons as `MQTT Device Triggers` in Home Assistant.
- Make sure `MQTT Discovery` is enabled in your Z2M configuration (default).

## Community import via URL (optional)

If you publicly host this repo (for example on GitHub), you can also import via `Add Blueprint` using a raw URL:

`https://raw.githubusercontent.com/<user>/<repo>/main/blueprints/automation/enocean_ptm215z_z2m.yaml`

After that, click the button `Import Blueprint to My Home Assistant` to add the blueprint.

