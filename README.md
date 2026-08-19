# View Assist

Welcome to my Home Assistant blueprints repository!

The following custom Home Assistant blueprints have been created for View Assist.

These blueprints add the missing functionality found in commercial systems, such as general knowledge questions, music control, alarms and TODO lists, without needing to write complex Jinja2 templates or YAML automations from scratch.

##### **Prerequisites**

Alarms are provided via a separate integration, [Voice Alarms](https://github.com/lone-baggie/voice_alarms). Music control is provided by Music Assistant. TODO lists use the standard Home Assistant integration. These Blueprints require dashboards to match the query. See Dashboards for examples.

---

## 📋 Blueprint Overview

| Blueprint                                                           | Category    | Description                                                    | Quick Import                                                                                                                                                                                                                                                                                                                                                                       |
|:------------------------------------------------------------------- |:----------- |:-------------------------------------------------------------- |:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [**VA Display music**](#1-va-display-music)                         | Display     | Displays music dashboard whenever media player plays           | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Display%2520Music.yaml)               |
| [**VA Gesture control**](#2-va-gesture-control)                     | Touch       | Displays dashboard according to swipe gesture                  | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Gesture%2520control.yaml)             |
| [**VA Sync volume**](#3-va-sync-volume)                             | Media       | Syncs physical volume with Music Assistant                     | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Sync%2520volume.yaml)                |
| [**VA Todo**](#4-va-todo)                                           | Application | Controls TODO/shopping list                                    | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Todo.yaml)                       |
| [**VA Turn off screen low light**](#5-va-turn-off-screen-low-light) | Maintenance | Turns off screen when low ambient light is detected            | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Turn%2520off%2520screen%2520low%2520light.yaml) |
| [**VA Display alarms**](#6-va-display-alarms)                        | Utility     | Displays active alarms                                         | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520display%2520alarm.yaml)               |
| [**VA Trigger alarm display**](#7-va-trigger-alarm-display)         | Display     | Triggers active alarms dashboard display                       | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520trigger%2520Alarm%2520display.yaml)      |

---

## 🛠️ Blueprints

---

### 1. VA Display Music

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Display%2520Music.yaml)

**File Path:** `VA Display Music.yaml`

#### Description

Displays music Dashboard if media player is playing.

---

### 2. VA Gesture control

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Gesture%2520control.yaml)

**File Path:** `VA Gesture control.yaml`

#### Description

Uses one and two fingers swipes, left and right to display alternative dashboard displays.

---

### 3. VA Sync volume

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Sync%2520volume.yaml)

**File Path:** `VA Sync volume.yaml`

#### Description

Keeps physical volume in sync with Music assistant.

---

### 4. VA Todo

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Todo.yaml)

**File Path:** `VA Todo.yaml`

#### Description

Home Assistant `to do` list management. Can also display list on screen.

#### Features

- Integrates directly with native Home Assistant To-Do lists.
- Allows adding and item removal.
- Option to delete all items.

---

### 5. VA Turn off screen low light

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Turn%2520off%2520screen%2520low%2520light.yaml)

**File Path:** `VA Turn off screen low light.yaml`

#### Description

Turns on and off screen according to light level.

#### Features

* Requires a physical light sensor to be present.

---

### 6. VA Display Alarms

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520display%2520alarm.yaml)

**File Path:** `VA display alarm.yaml`

#### Description

Display Alarm dashboard with voice.

---

### 7. VA Trigger Alarm display

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520trigger%2520Alarm%2520display.yaml)

**File Path:** `VA trigger Alarm display.yaml`

#### Description

Triggers dashboard view when alarm is updated.

---

### 8. AVA music assistant

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FAVA%2520music%2520assistant.yaml)

**File Path:** `AVA music assistant.yaml`

#### Description

Voice control for **Music Assistant** integration in Home Assistant.

#### Features

* Play music by song, artist, album or radio  
* Volume control  
* Jump track forward and backwards  
* Play on remote speaker

---

### 9. Auto ducking volume

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FAuto%2520ducking%2520volume.yaml)

**File Path:** `Auto ducking volume.yaml`

#### Description

Automatically dips (ducks) the background audio volume on playing media players in the same area as the AVA device. It also allows another area to be added to allow portable speakers to be included.

---

### 10. VA LLM Music Assistant

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FLLM%2FAVA%2520LLM%2520Music%2520Assistant.yaml)

**File Path:** `LLM/AVA LLM Music Assistant.yaml`

#### Description

An LLM-assisted version of the AVA Music Assistant blueprint, providing natural language processing for queries and commands related to Music Assistant playback.

---

## 🚀 How to Install

### Option 1: Automatic 1-Click Import (Recommended)

Click any of the **Import Blueprint** badges above. Home Assistant will open the import wizard with the exact blueprint raw path pre-filled.

### Option 2: Manual URL Import

1. In Home Assistant, go to **Settings** -> **Automations & Scenes** -> **Blueprints**.  
2. Click **Import Blueprint** in the bottom right corner.  
3. Paste the URL of the file from this repository.  
4. Click **Import Blueprint**.

---

## 🐞 Issues & Contributions

Found a bug or have a suggestion for improving these blueprints? Please open an issue or submit a pull request on the [GitHub Repository](https://github.com/lone-baggie/home-assistant-blueprints/issues).

---

*Created with ❤️ for the Home Assistant Community.*
