# Steel Seed RenoDX HDR

A RenoDX HDR modification for **Steel Seed** that adds comprehensive HDR support, custom tonemapping, and advanced color grading options.

## Features

- **HDR Support**: HDR10
- **Advanced Color Grading**: Fine-tune brightness, contrast, saturation, and color balance
- **Real-time Adjustments**: All settings can be adjusted in real-time via the ReShade overlay

## Requirements

- **Steel Seed** (Steam version recommended)
- **ReShade with Add-on Support** (Required for RenoDX functionality)
- **HDR-capable display** (for HDR features)
- **Windows 10/11** with HDR enabled in display settings

## Installation

### Step 1: Install ReShade with Add-on Support

1. Download **ReShade** with full addon support from [reshade.me](https://reshade.me/)
2. Run the ReShade installer
3. Select **Steel Seed executable**: `SteelSeed\Binaries\Win64\SteelSeed-Win64-Shipping.exe`
4. Choose **DirectX 10/11/12**
6. Skip shader selection (not needed for this mod)

### Step 2: Install RenoDX HDR Mod

1. Download `renodx-steelseed.addon64` from the [Releases](../../releases) page
2. Copy the file to your Steel Seed installation directory: SteelSeed\Binaries\Win64\renodx-steelseed.addon64
3. 3. The file should be in the same folder as `SteelSeed-Win64-Shipping.exe`

### Step 3: Configure HDR (Optional)

For HDR displays:
1. Enable HDR in Windows Display Settings
2. Set your display to HDR mode if it needs to be manually selected; it should automatically detect HDR when you enable HDR in Windows Display Settings.
3. Launch Steel Seed
4. Open ReShade overlay (Home key by default)
5. Navigate to RenoDX settings and select the appropriate HDR settings

## Usage

### Accessing RenoDX Settings

1. Launch Steel Seed
2. Press **Home** key to open ReShade overlay
3. Navigate to the **Add-ons** tab
4. Find **RenoDX** settings

### Key Settings

#### HDR Configuration
- **HDR Peak Nits**: Choose based on your display peak brightness
- **Game Nits**: Adjust based on game's brightness (typically 100-203 nits, increaase this to make game brighter without increasing the peak nits of your display)
- **UI Paper White**: Control UI element brightness separately
-  **Gamma Correction**: Control between 2.2, 2.4/BT1886

#### Tonemapping Options
- **Tonemapping Type**: Choose from various curve options:
  - Vanilla (Original game tonemapping) (SDR)
  - RenoDRT (Real and true HDR10 tonemapping)

#### Color Grading
- **Brightness**: Global brightness adjustment
- **Contrast**: Contrast enhancement
- **Saturation**: Color saturation control
- **Color Temperature**: Warm/cool color balance
and more...

## Known Issues
- **Brightness**: Game is too dark. Use Game brightness/shadows/contrast sliders to adjust game brightness. Will be fixed soon.. 

## Troubleshooting

### Mod Not Loading
- Ensure ReShade was installed with **Add-on Support** enabled
- Verify `renodx-steelseed.addon64` is in the correct directory
- Check ReShade overlay shows RenoDX in the Add-ons tab

### Poor HDR Performance
- Lower HDR peak nits setting
- Adjust Game Nits to match your display capabilities
- Ensure Windows HDR is properly configured

### Color Issues
- Reset RenoDX settings to defaults
- Adjust tonemapping type
- Check display color profile settings

## Screenshots

*None

## Technical Details

- **Engine**: Unreal Engine 5
- **Rendering API**: DirectX 12
- **RenoDX Version**: Compatible with latest RenoDX framework
- **Game Version**: Tested with current Steam version

## Contributing

Found a bug or have suggestions? Please open an issue on this repository.

## Credits

- **RenoDX Framework**: [clshortfuse/renodx](https://github.com/clshortfuse/renodx)
- **ReShade**: [crosire/reshade](https://github.com/crosire/reshade)
- **Steel Seed**: [Game Developer]

---

**Enjoy enhanced HDR gaming in Steel Seed!**

## Disclaimer

This mod does not include any original game assets or proprietary files. It is an unofficial modification and is not affiliated with or endorsed by the developers of Steel Seed or RenoDX. All trademarks and copyrights belong to their respective owners.

## License

The compiled mod file `renodx-steelseed.addon64` and all accompanying files in this repository are licensed under the MIT License. You are free to use, share, and modify this mod under the terms of the MIT License. See [https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT) for details.

