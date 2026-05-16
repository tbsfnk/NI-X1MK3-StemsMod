# Traktor X1 MK3 – Stems Control QML Mod

A QML mod for the Native Instruments Traktor Kontrol X1 MK3 that repurposes the mixer mode knobs and EQ buttons to control stems.

## Features

- **Stems control via knobs and EQ buttons** – In mixer mode, the knobs and buttons are mapped to control individual stem volumes and mutes.
- **Screen feedback** – The X1 MK3 screen displays visual feedback for stem controls.
- **EQ logic preserved with Shift** – Hold Shift to access the original EQ functionality.
- **Key control** – The last knob and button are remapped to control the track key.
- **All other functions unchanged** – Every other function of the X1 MK3 stays default.

## Compatibility

- **Traktor Pro 4** version 4.4.2 (tested)
- Native Instruments Kontrol X1 MK3

## Installation

> **⚠️ Disclaimer:** Use this mod at your own risk. I take no responsibility for any damage, data loss, or issues caused by installing or using this modification.

1. Back up the **entire** `C:\Program Files\Native Instruments\Traktor Pro 4\Resources64\qml` folder to a safe location.
2. Copy the `qml/` folder from this repository into `C:\Program Files\Native Instruments\Traktor Pro 4\Resources64\`, replacing the existing files when prompted.
3. Restart Traktor.

## Usage

1. Switch the X1 MK3 to **Mixer Mode**.
2. Use the knobs to control stem volumes and the EQ buttons to mute/unmute stems.
3. Hold **Shift** to access the original EQ controls. The last knob and button control the track key

## File Structure

```
qml/
├── CSI/
│   └── X1MK3/
│       └── X1MK3FXSectionSide.qml
└── Screens/
    └── X1MK3/
        └── FXScreen.qml
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
