# ZMK Configuration for DRESSTHING

Generated from QMK info.json

## Keyboard Information
- Name: DRESSTHING
- Type: Unibody
- Normalized Name: dressthing
- Board: bmp_boost

## Files Structure

### Unibody Keyboard Files
- boards/shields/dressthing/dressthing.overlay - Hardware definition
- boards/shields/dressthing/dressthing.conf - Configuration

### Common Files
- boards/shields/dressthing/layouts.dtsi - Physical layout definition
- boards/shields/dressthing/Kconfig.defconfig - Default configuration
- boards/shields/dressthing/Kconfig.shield - Shield configuration
- boards/shields/dressthing/dressthing.zmk.yml - ZMK metadata
- boards/shields/dressthing/dressthing.keymap - Shield keymap include
- config/keymap.keymap - Keymap definition
- config/info.json - Keyboard layout information for keymap editors
- config/west.yml - West manifest for ZMK dependencies
- build.yaml - Build configuration for ZMK
- zephyr/module.yml - Zephyr module configuration
- .github/workflows/build.yml - GitHub Actions workflow for building firmware

## Usage
1. Copy all files to your ZMK config repository
2. Customize the keymap in config/keymap.keymap as needed
3. Push to GitHub to trigger automatic firmware builds

## Board Information
This configuration is set up for bmp_boost. The board is from sekigon-gonnoc's repository.
