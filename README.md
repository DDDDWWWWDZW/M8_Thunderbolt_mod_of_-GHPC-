# XM8 Buford for Gunner HEAT PC

## Description

- This mod adds the **XM8 Buford** (M8 Armored Gun System) light tank to GHPC as a brand-new vehicle, not a replacement of any vanilla unit. One unit spawns automatically on the shooting range map; on other maps it is available through the custom vehicle menu.
- The exterior model is retopologized and re-segmented from the War Thunder XM8, the running gear is built from scratch (own wheels, suspension arms, sprockets and skinned tracks), and the interior is an original X-ray model.
- 一个 XM8「Buford」轻坦模组：自建履带行走装置、120mm XM291 火炮、109 块 L3 附加复合装甲，以及可剖视的内构与损伤模型。

## Download

Use the release asset:

```text
XM8-1.0.0-official.zip
```

## Requirements

- **MelonLoader 0.7.x (net472)** for Gunner HEAT PC
- Gunner HEAT PC (current Steam build)

## Install

1. Install **MelonLoader 0.7.x (net472)** for Gunner HEAT PC.
2. Extract the `XM8` folder from the zip into:

```text
<GHPC install>\Bin\Mods
```

3. Start the game. The XM8 spawns automatically on the shooting range.

## Contents

- Brand-new vehicle `XM8 Buford`, registered as its own unit (does not replace the T-80B)
- XM291 120 mm gun with the M1A2C ammunition set: M829E2 / M829E3 / M829E4 APFSDS, M830 / M830A1 HEAT
- 30-round loadout (15 AP + 6 HEAT in the autoloader, 6 AP + 3 HEAT in the hull rack), automatic loader cycle
- Original running gear: 6 road wheels per side, drive sprocket, idler, swing arms and skinned tracks
- External **Level III composite add-on armour**: 109 individually armoured plates, each with its own KE/CE RHAe, correct hull/turret/gun attachment (the gun plates elevate with the barrel) and semi-transparent AAR/X-ray visuals
- Add-on armour can be toggled off to run the bare XM8 hull model
- Interior model with X-ray parts: engine, transmission, turret drives, breech, autoloader, optics, fuel tanks, crew stations, composite armour arrays
- Interior damage model: engine, transmission, traverse/elevation drives, XM291 breech and barrel, autoloader, gunner and commander sights, machine guns, fuel tanks with flammability, interior bulkheads
- Reworked olive green base paint (unified tone, preserved panel detail, darkened running gear rubber)
- Tuned handling and weapon drives: 580 hp at 2400 rpm, 21.0 t bare / 25.8 t with the L3 kit, 72 km/h forward, 27 km/h reverse
- Turret traverse 40°/s, gun elevation 14°/s, elevation limits −8° to +20°
- Third-person camera centred on the XM8 model, commander view on the cupola hatch, co-axial machine gun muzzle aligned to the model and elevating with the gun
- IPM1-style crew postures for gunner and commander

## Relevant entries

Preferences are written to `<GHPC install>\Bin\UserData\MelonPreferences.cfg` on first launch:

```ini
[ XM8 ]

"Install Level III add-on armour" = true  # ON: L3 composite kit bolted on. OFF: bare hull model.
"AP Ammo (XM8)" = "M829E4"                # M829E2 / M829E3 / M829E4, applied at startup
```

## Notes

- The exterior model is derived from the War Thunder XM8; I performed the retopology and re-segmentation so it works as an in-game vehicle. All rights reserved. Redistribution, modification and commercial use are not permitted without written permission.
- This is a compiled distribution; modify/redistribute only with permission.
- If you wish to modify and release your own version based on this mod, please notify me.
- This mod was created with the assistance of AI.
- Special thanks to the GHPC modding community for the tooling and reference material.
