# Zigbee Drivers for SmartThings Edge

The majority of the *SmartThings Edge Drivers* that are supported at this repository were developed and tested on devices that are already compatible with *SmartThings*, with the exception of the [button-battery](./button-battery) driver that integrates a non-certified Tuya product into the _SmartThings Ecosystem_.

If your device isn't supported and you want to contribute to this repository, you can either submit a _Pull Request_ or you can find me at [SmartThingsCommunity](https://community.smartthings.com/u/erickv/).

**These drivers are available at the **[@erickv Shared Drivers](https://api.smartthings.com/invite/Q1jP18n4oZML)** channel.**

---

## Drivers

### [button-battery](./button-battery)
```yaml
zigbeeManufacturer:
  # 4-gang MOES Scene Switch
  manufacturer: "_TZ3000_xabckq1v"
  model: "TS004F"
```

### [switch-level-color-bulb](./switch-level-color-bulb)
```yaml
zigbeeManufacturer:
  # Sengled Soft White Bulb
  manufacturer: "sengled"
  model: "E11-G13"
```

### [switch-power-outlet](./switch-power-outlet)
```yaml
zigbeeManufacturer:
  # Samjin/SmartThings Outlet
    manufacturer: "Samjin"
    model: "outlet"

  # Sonoff Outlet
    manufacturer: "SONOFF"
    model: "S31 Lite zb"
```