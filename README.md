Street Management System: Vehicle Speed Tracking and Smart Street Lighting

## Overview

This project implements a Smart Street Management System with two major components:

* Smart Street Lighting System
* Vehicle Speed Detection System

The goal is to automate street lighting and detect over-speeding vehicles with high accuracy.


## Smart Street Lighting

The Smart Street Lighting System adjusts lighting based on:

* Surrounding illumination detected using an LDR
* Motion detection to activate LEDs

When illumination is low, the LDR resistance falls, allowing current flow. If motion is detected, LEDs turn on automatically.

---

## Vehicle Speed Detection

The Vehicle Speed Detection System monitors vehicle speed and:

* Identifies over-speeding vehicles

This system provides improved efficiency compared to manual monitoring.


---

## How to Run

### 1. Upload to Wokwi

Upload the simulation folders to **Wokwi**.

### 2. Add ThingSpeak Credentials

Inside:

```
./<SIMULATION_NAME>/sketch.ino
```

Replace:

* `{{ API_KEY }}`
* `{{ CHANNEL_NUM }}`
  with your actual **ThingSpeak API key and channel number**.

### 3. Run Simulations

Start the simulations on Wokwi.

---

## Requirements

* Python 3.x
* ThingSpeak API Key
* Power BI Desktop
* Wokwi Account

---

## Authors

* Abdullah Hussain
* Jaweria Manahil
* Saif Sheikh
* Sara Adnan
* Zainab Athar

---

