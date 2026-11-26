# XM8 Thunderbolt for Gunner HEAT PC

## Description

- Author:芝士大嘴蛙（DDDDWWWWDZW）
-This mod adds the M8 Thunderbolt tank to GHPC. You can test it on the range, or select it via custom vehicles on other maps. It is available for both tank and IFV missions. The model is sourced from War Thunder and retopologized by me. All mod features are implemented by myself. This is a personal fan mod and is not affiliated with any game developers.
- 一个 XM8「Thunderbolt」轻坦模组：120mm XM291 火炮、 可选的L3级别附加复合装甲，自动装弹机和抛壳动画、M1A2级别的火控，以及专属M8的内构与损伤模型。



## Requirements

- **MelonLoader 0.7.x+ (net472)** for Gunner HEAT PC
- Gunner HEAT PC (current Steam build)

## Install

1. Install **MelonLoader 0.7.x (net472)** for Gunner HEAT PC.
2. Extract the `XM8` folder from the zip into:

```text
<GHPC install>\Bin\Mods
```

3. Start the game. The XM8 spawns automatically on the shooting range.

## Contents

- Brand-new vehicle `XM8 Thunderbolt`, registered as its own unit
- XM291 120 mm gun with the M1A2C ammunition set: M829E2 / M829E3 / M829E4 APFSDS, M830A1 HEAT
- 30-round loadout (15 AP + 6 HEAT in the autoloader, 6 AP + 3 HEAT in the hull rack), automatic loader cycle
- Original running gear: 6 road wheels per side, drive sprocket, idler, swing arms and skinned tracks
- External **Level III composite add-on armour**: 109 individually armoured plates, each with its own KE/CE RHAe, correct hull/turret/gun attachment (the gun plates elevate with the barrel) and semi-transparent AAR/X-ray visuals
- Add-on armour can be toggled off to run the bare XM8 hull model
- Interior model with X-ray parts: engine, transmission, turret drives, breech, autoloader, optics, fuel tanks, crew stations, composite armour arrays
- Interior damage model: engine, transmission, traverse/elevation drives, XM291 breech and barrel, autoloader, gunner and commander sights, machine guns, fuel tanks with flammability, interior bulkheads
- Reworked olive green base paint (unified tone, preserved panel detail, darkened running gear rubber)
- Tuned handling and weapon drives: 580 hp at 2400 rpm, 21.0 t bare / 25.8 t with the L3 kit, 72 km/h forward, 27 km/h reverse
- Turret traverse 40°/s, gun elevation 24°/s, elevation limits −8° to +20°
- Third-person camera centred on the XM8 model, commander view on the cupola hatch, co-axial machine gun muzzle aligned to the model and elevating with the gun
<img width="1494" height="908" alt="87a47a40116630ca48e99f6577b3daba" src="https://github.com/user-attachments/assets/6874f99b-7e60-435a-b500-c69d3bf63c22" />
<img width="1469" height="868" alt="03ce68b60f2ab06bb563203a35146679" src="https://github.com/user-attachments/assets/0856621d-c31b-416c-b73a-a73e4357cba2" />


## Relevant entries

Preferences are written to `<GHPC install>\Bin\UserData\MelonPreferences.cfg` on first launch:

```ini
[ XM8 ]

"Install Level III add-on armour" = true  # ON: L3 composite kit bolted on. OFF: bare hull model.
"AP Ammo (XM8)" = "M829E4"                # M829E2 / M829E3 / M829E4, applied at startup
```

## Notes

- The exterior model is derived from the War Thunder XM8; I performed the retopology and re-segmentation so it works as an in-game vehicle. Redistribution, modification and commercial use are not permitted without written permission.The copyright of the original 3D model belongs to Gaijin Entertainment (Gaijin Network Ltd).
- This is a compiled distribution; modify/redistribute only with permission.
- If you wish to modify and release your own version based on this mod, please notify me.
- This mod was created with the assistance of AI.
