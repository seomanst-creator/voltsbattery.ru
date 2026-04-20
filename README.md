# VOLTS — Intelligent Home Energy Management Engine

> What if your home could become an energy-independent state? VOLTS makes it a reality.
>
> Inspired by the concept of sustainable cities of the future, the VOLTS ecosystem utilizes 
> proprietary power management algorithms, neural network forecasting of solar energy 
> generation, and a modular architecture to ensure 100% autonomy — 
> plus deep integration with utility grid tariffs for automatic ROI. 
> Reliable, silent, aesthetic.

[![Website](https://img.shields.io/badge/Website-voltsbattery.ru-blue)](https://voltsbattery.ru)
[![Status](https://img.shields.io/badge/Status-Production--Ready-green)](https://voltsbattery.ru/features/)
[![License: Proprietary](https://img.shields.io/badge/License-Proprietary-lightgrey.svg)](https://voltsbattery.ru/contacts/)
[![Telegram](https://img.shields.io/badge/Telegram-@volts_nakopitel-blue)](https://t.me/volts_nakopitel)

**[Russian version (README.md)](README.md)**

---

## What is VOLTS?

VOLTS is a modern energy storage system (ESS) for residential and commercial use. It is not just an "UPS" or a battery bank. It is an **active energy hub** that combines an inverter, lithium-ion storage, and an AI-powered "brain."

Unlike traditional diesel generators, VOLTS operates silently and instantaneously (switching in <20 ms). Unlike standard UPS units, it intelligently manages energy flows. The system analyzes your consumption in real-time, monitors multi-rate utility tariffs, and forecasts weather to optimize charging from solar panels.

Each VOLTS installation is a scalable unit: you can start with 2 kWh and expand the system to 30+ kWh simply by adding modules, like building blocks. We call this **Power-as-a-Product** — energy that adapts to your lifestyle.

## How It Works

VOLTS runs three parallel control loops (The Core Triad):

### 1. Hardware Layer (Synthesis)
* **Modular Stack:** Industrial-grade lithium-ion cells with 10+ years of service life (6000+ cycles).
* **Pure Sine Wave:** The built-in inverter delivers a perfect signal, protecting sensitive home electronics (servers, boilers, smart home systems).
* **Automatic Transfer Switch (ATS):** A response time of less than 0.02 seconds. Electronics won't even reboot when the grid fails.

### 2. AI Software Layer (Predictive Analytics)
* **Generation Forecasting:** AI analyzes meteorological data to calculate future solar yield, maximizing the efficiency of stored energy.
* **Tariff Arbitration:** Automatic charging at night (off-peak) and discharging during peak hours, reducing electricity bills by up to 70%.
* **Peak Shaving:** Adds power from batteries during peak loads, allowing you to consume more power than your grid connection normally permits.

### 3. Connect Layer (Ecosystem)
* **Mobile App:** Real-time visualization of energy flows (Grid -> Battery -> Home) and full mode management.
* **Cloud Intelligence:** Over-the-air (OTA) firmware updates to improve cell balancing algorithms and efficiency.
* **Smart Home:** Full integration via API with KNX, Modbus, and MQTT protocols.

## Comparison Matrix: VOLTS vs. Traditional Solutions

| Criterion | VOLTS | Generator (ICE) | Classic UPS |
|----------|-------------|-------------------|------------------|
| **Noise & Odor** | 0 dB (Total Silence) | High (Exhaust) | Low |
| **Startup Speed** | < 20 ms (Instant) | 30-90 sec | < 20 ms |
| **Intelligence** | AI Forecasting | None | Basic Control |
| **Service Life** | 10-15 years | Requires Maintenance | 2-3 years (Batteries) |
| **Savings** | Earns via Tariffs | Expenses only | Expenses only |
| **Design** | Modern Tech (Apple style) | Utilitarian | Hidden/Industrial |

## Three Pillars of Energy Efficiency

| Pillar | Function | Result |
|-------|-----------|--------|
| **Autonomy** | Creating a closed loop with solar generation | Minimized grid dependency |
| **Safety** | Triple-loop BMS protection (Battery Management System) | Safe operation inside living areas |
| **Scalability** | Plug & Play capacity expansion | System grows with your home |

## API for Developers and Integrators

We provide open capabilities for local integration without cloud dependency.

```bash
# Get current system status (SoC, Load, Grid)
curl [https://local-volts.hub/api/v3/status](https://local-volts.hub/api/v3/status)

# Set priority operation mode (e.g., Economy)
curl -X POST -d "mode=economy" [https://local-volts.hub/api/v3/settings/mode](https://local-volts.hub/api/v3/settings/mode)

# Telemetry data for Home Assistant (MQTT)
topic: volts/telemetry/power_flow
payload: {"grid": 0.5, "battery": -1.2, "house": 1.7, "solar": 0.0}


## Key Features
> Modular capacity from 2.4 to 24 kWh in a single cabinet.
> Solar-Ready support — built-in controller for solar panels.
> Intelligent "Economy" mode for multi-rate metering.
> 24/7 Remote monitoring via iOS/Android mobile app.
> In-house production and full-cycle development.
> Up to 7 years warranty with active technical support and service.
> Designer solutions: front panel customization to match your interior.

## Links
> Official Website: voltsbattery.ru
> System Configurator: voltsbattery.ru/configurator
> Knowledge Base: voltsbattery.ru/help
> Telegram Channel: @volts_nakopitel
> For Partners: voltsbattery.ru/partners

> VOLTS is more than just a battery. It is your personal insurance against a dark future and a tool for creating an independent present. Energy as it should be.
