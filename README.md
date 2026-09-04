# View Assist

Welcome to View Assist assets for the Facebook Portal 

The following custom Home Assistant blueprints and dashboards have been created for View Assist.

These blueprints and dashboards , have been created for the Facebook Portal Gen 2, 8 and 10” versions.

##### **Prerequisites**

Alarms are provided via a separate integration, [Voice Alarms](https://github.com/lone-baggie/voice_alarms). Music control is provided by Music Assistant. TODO lists use the standard Home Assistant integration. These blueprints require dashboards to be created to match the query. See [Dashboards](https://github.com/lone-baggie/View-Assist/tree/main/Dashboards) for examples. 

The dashboard examples supplied must be added to the original View-Assist dashboard, as they contain variables obtained from the default dashboard. To add one of the dashboard YAML files views to the existing view-assist dashboard:

* Edit existing View Assist dashboard  
* Add a new view. Ensure the name of the view is the same as the YAML file you wish to use.  
* Ensure the view created is panel view (one card).  
* Once created, add a new card. Select the manual card.  
* Delete file contents of the manual card.  
* Cut and paste the YAML file contents into the blank card and save.

There is also a complete example dashboard.yml. Simply create a new dashboard and select the raw configuration editor. Delete any existing code and paste the entire script and save. 
**Note some of the individual views now require variables created in the dashboard. yml** 


---

## 📋 Blueprint Overview

| Blueprint | Category | Description | Quick Import |
| :---- | :---- | :---- | :---- |
| [**VA Display music**](#1-va-display-music) | Display | Displays a music dashboard whenever the media player plays | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Display%2520Music.yaml) |
| [**VA Gesture control**](#2-va-gesture-control) | Touch | Displays dashboard according to swipe gesture | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Gesture%2520control.yaml) |
| [**VA Sync volume**](#3-va-sync-volume) | Media | Syncs physical volume with Music Assistant | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Sync%2520volume.yaml) |
| [**VA Todo**](#4-va-todo) | Application | Controls TODO/shopping list | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Todo.yaml) |
| [**VA Turn off screen low light**](#5-va-turn-off-screen-low-light) | Maintenance | Turns off screen when low ambient light is detected | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Turn%2520off%2520screen%2520low%2520light.yaml) |
| [**VA Display alarms**](#6-va-display-alarms) | Utility | Displays active alarms | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520display%2520alarm.yaml) |
| [**VA Trigger alarm display**](#7-va-trigger-alarm-display) | Display | Triggers active alarms dashboard display | [![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520trigger%2520Alarm%2520display.yaml) |

---

## 🛠️ Blueprints

---

### 1\. VA Display Music

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Display%2520Music.yaml)

**File Path:** `VA Display Music.yaml`

#### Description

Displays the music dashboard if the media player is playing.

---

### 2\. VA Gesture Control

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Gesture%2520control.yaml)

**File Path:** `VA Gesture control.yaml`

#### Description

Uses one- and two-finger swipes, left and right, to display alternative dashboard views.

---

### 3\. VA Sync volume

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Sync%2520volume.yaml)

**File Path:** `VA Sync volume.yaml`

#### Description

Keeps physical volume in sync with Music Assistant.

---

### 4\. VA Todo

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Todo.yaml)

**File Path:** `VA Todo.yaml`

#### Description

Home Assistant `todo` list management. Can also display a list on screen.

#### Features

- Integrates directly with native Home Assistant To-Do lists.  
- Allows adding and item removal.  
- Option to delete all items.

---

### 5\. VA Turn off screen low llight.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520Turn%2520off%2520screen%2520low%2520light.yaml)

**File Path:** `VA Turn off screen low light.yaml`

#### Description

Turns on and off screen according to light level.

---

### 6\. VA Display Alarms

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520display%2520alarm.yaml)

**File Path:** `VA display alarm.yaml`

#### Description

The display shows the alarm view using voice trigger.

---

### 7\. VA Trigger Alarm display

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FVA%2520trigger%2520Alarm%2520display.yaml)

**File Path:** `VA trigger Alarm display.yaml`

#### Description

Triggers the dashboard view when the alarm is updated.

---

### 8\. VA music assistant

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FAVA%2520music%2520assistant.yaml)

**File Path:** `VA music assistant.yaml`

#### Description

Voice control for **Music Assistant** integration in Home Assistant.

#### Features

* Play music by song, artist, album or radio  
* Volume control  
* Jump track forward and backwards  
* Play on remote speaker

---

### 9\. Auto-duckingvolume

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FAuto%2520ducking%2520volume.yaml)

**File Path:** `Auto-ducking volume. yaml`

#### Description

Automatically dips (ducks) the background audio volume on playing media players in the same area as the AVA device. It also allows another area to be added to allow portable speakers to be included.

---

### 10\. VA LLM Music Assistant

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.]()](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Flone-baggie%2Fhome-assistant-blueprints%2Fblob%2Fmain%2FLLM%2FAVA%2520LLM%2520Music%2520Assistant.yaml)

**File Path:** `LLM/VA LLM Music Assistant.yaml`

#### Description

An LLM-assisted version of the AVA Music Assistant blueprint, providing natural language processing for queries and commands related to Music Assistant playback.

---

## 🚀 How to Install

### Option 1: Automatic 1-Click Import (Recommended)

Click any of the **Import Blueprint** badges above. Home Assistant will open the import wizard with the exact blueprint raw path pre-filled.

### Option 2: Manual URL Import

1. In Home Assistant, go to **Settings** \-\> **Automations & Scenes** \-\> **Blueprints**.  
2. Click **Import Blueprint** in the bottom right corner.  
3. Paste the URL of the file from this repository.  
4. Click **Import Blueprint**.

---

## 🐞 Issues & Contributions

Found a bug or have a suggestion for improving these blueprints? Please open an issue or submit a pull request on the [GitHub Repository](https://github.com/lone-baggie/home-assistant-blueprints/issues).

---

*Created with ❤️ for the Home Assistant Community.*  
