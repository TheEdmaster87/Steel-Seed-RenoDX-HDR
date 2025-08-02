# Steel Seed RenoDX HDR

A RenoDX HDR modification for **Steel Seed** that adds comprehensive HDR support, custom tonemapping, and advanced color grading options.

## Features

- **HDR Support**: HDR10, HDR400, HDR1000, and HDR4000 profiles
- **Custom Tonemapping**: Multiple tonemapping curve options for different visual styles
- **Advanced Color Grading**: Fine-tune brightness, contrast, saturation, and color balance
- **Real-time Adjustments**: All settings can be adjusted in real-time via the ReShade overlay

## Requirements

- **Steel Seed** (Steam version recommended)
- **ReShade with Add-on Support** (Required for RenoDX functionality)
- **HDR-capable display** (for HDR features)
- **Windows 10/11** with HDR enabled in display settings

## Installation

### Step 1: Install ReShade with Add-on Support

1. Download **ReShade** from [reshade.me](https://reshade.me/)
2. Run the ReShade installer
3. Select **Steel Seed executable**: `SteelSeed\Binaries\Win64\SteelSeed-Win64-Shipping.exe`
4. Choose **DirectX 10/11/12**
5. **Important**: Make sure to check **"Enable Add-on Support"** during installation
6. Skip shader selection (not needed for this mod)

### Step 2: Install RenoDX HDR Mod

1. Download `renodx-steelseed.addon64` from the [Releases](../../releases) page
2. Copy the file to your Steel Seed installation directory: SteelSeed\Binaries\Win64\renodx-steelseed.addon64
3. 3. The file should be in the same folder as `SteelSeed-Win64-Shipping.exe`

### Step 3: Configure HDR (Optional)

For HDR displays:
1. Enable HDR in Windows Display Settings
2. Set your display to HDR mode
3. Launch Steel Seed
4. Open ReShade overlay (Home key by default)
5. Navigate to RenoDX settings and select appropriate HDR profile

## Usage

### Accessing RenoDX Settings

1. Launch Steel Seed
2. Press **Home** key to open ReShade overlay
3. Navigate to the **Add-ons** tab
4. Find **RenoDX** settings

### Key Settings

#### HDR Configuration
- **HDR Peak Nits**: Choose HDR400, HDR1000, or HDR4000 based on your display
- **Game Nits**: Adjust based on game's brightness (typically 100-203 nits)
- **UI Paper White**: Control UI element brightness separately
- **HDR10 PQ**: Enable for proper HDR10 output

#### Tonemapping Options
- **Tonemapping Type**: Choose from various curve options:
  - Vanilla (Original game tonemapping)
  - ACES
  - Reinhard
  - Custom curves
- **Tone Map Gamma**: Fine-tune gamma correction
- **Tone Map Exposure**: Adjust overall exposure

#### Color Grading
- **Brightness**: Global brightness adjustment
- **Contrast**: Contrast enhancement
- **Saturation**: Color saturation control
- **Color Temperature**: Warm/cool color balance
- **Tint**: Magenta/green color shift

#### Film Grain
- **Film Grain**: Enable/disable film grain effect
- **Film Grain Intensity**: Control grain strength

## Known Issues

- **UI Brightness**: UI brightness controls affect the entire scene brightness (common Unreal Engine 5 limitation)
- **Performance**: Minimal performance impact (~1-2% depending on settings)

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

## License

This modification is provided as-is for educational and enhancement purposes.

---

**Enjoy enhanced HDR gaming in Steel Seed!**
