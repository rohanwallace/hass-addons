<div align="center">

# Add-ons — Home Assistant

**Home Assistant add-on repository originally developed and maintained by [Domodom30](https://github.com/domodom30).**

[![HA](https://img.shields.io/badge/Home%20Assistant-compatible-41BDF5?style=flat-square&logo=homeassistant)](https://www.home-assistant.io/)

</div>

---

## 📦 Repository Installation

1. In Home Assistant, open **Settings → Apps → Install App**.
2. Open the **⋮** menu (top right) → **Repositories**.
3. Add the URL: `https://github.com/rohanwallace/hass-addons`
4. The add-ons listed below will appear in the Add-on Store.

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Frohanwallace%2Fhass-addons)

---

## 🧩 Available Add-ons

| Add-on | Version | Description | Architectures |
|---|---|---|---|
| [**TTLock**](./ttlock-hass-integration) | `2.7.6` | Integration for TTLock smart locks via BLE, **without the cloud**. | amd64, armv7, armhf, i386, aarch64 |
| [**Bluetooth Audio Manager**](./ha-bluetooth-audio-manager) | `3.3.6` | Management of Bluetooth audio devices (A2DP) with persistent pairing and automatic reconnection. | aarch64, amd64, armv7, armhf |

---

### 🔑 TTLock

> Integrate your TTLock smart locks directly into Home Assistant — no cloud required.

- **Lock control** — pairing, locking/unlocking (UI or MQTT), real-time status (state, battery, RSSI).
- **Access management** — PIN codes, IC cards and fingerprints (add, modify, delete, aliases).
- **Settings** — auto-lock, confirmation beep, clock synchronization and operation logs.
- **Home Assistant integration via MQTT** — automatic MQTT Discovery, `lock` entity, battery/RSSI sensors, firmware exposed as `sw_version`.
- **Remote BLE gateway** — compatible with the [ESP32 BLE Gateway](https://github.com/domodom30/esp32-ble-gateway) if the Home Assistant server does not have Bluetooth or the locks are out of range.

📖 [Full documentation](./ttlock-hass-integration/README.md)

---

## 🔗 Useful Links

- 🐛 [Report a bug](https://github.com/rohanwallace/hass-addons/issues)
- 📦 [Original TTLock SDK Fork](https://github.com/domodom30/ttlock-sdk-js)
- 📡 [ESP32 BLE Gateway](https://github.com/domodom30/esp32-ble-gateway)

---

<div align="center">
<sub>Originally developed with ❤️ for the Home Assistant community by Domodom30.</sub>
</div>
