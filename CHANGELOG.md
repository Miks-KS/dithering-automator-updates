# D1TH3R1NG 4UTOM4TOR - Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [1.1.0] - 2025-07-08

### ✨ **New Features**

#### **Auto-Sort Color Palette**
- Added auto-sort functionality for Custom Palette color swatches
- New auto-sort button (Flare Icon) next to "Current Palette" header
- Sorts colors from darkest to lightest based on luminance
- Purely cosmetic feature - no impact on dithering algorithms or color mapping
- Makes it easier to visualize color gradients and transitions in your palette
- You can click this button every time you want to clean up your palette and sort it again after adding new colors, for example

#### **Image Adjustment Reset Control**
- Added new "Behavior" tab in Preferences (Settings > Preferences/Settings)
- New preference option to control whether image adjustments (brightness, contrast, levels, etc.) are automatically reset when uploading new images
- Setting only applies when no custom preset is active - preset image adjustments are always preserved
- Option is enabled by default to maintain current behavior

### 🐛 **Bug Fixes**

#### **Sharpen Slider Improvements**
- **Fixed:** Sharpen slider positions 6-10 had no effect
- The Sharpen slider now provides progressive sharpening intensity across the full 0-10 range

---

## [1.0.0] - 2025-07-01

### Initial Release

This is the first release of D1TH3R1NG 4UTOM4TOR!

### Key Features

#### 30+ Dithering Algorithms
- **Error diffusion**: Floyd-Steinberg, Atkinson, Burkes, Sierra, and more
- **Ordered dithering**: Bayer matrices (2x2, 4x4, 8x8, 16x16)
- **Other dithering types**: 1D, frequency modulation, blue noise, pattern, clustered dot, etc.
- **Custom dithering patterns**: Create and edit your own dithering patterns

#### User Interface
- **Real time preview**: Instant preview update on your image when adjusting parameters
- **Zoom and drag-to-pan**: interactive preview canvas to get a better look at details
- **Multi-scale UI**: Support for 100%, 125%, 150%, and 200% scaling (for high DPI monitors)

#### Color Management
- **Custom palettes**: Create and manage color palettes
- **Color presets**: Built-in presets + option to create your own presets
- **Color extraction**: Automatic palette generation from images with k-means

#### Transparency Support
- **Transparency for PNG**: when you import a PNG with transparent background, transparency will be preserved
- **1-color images**: in the app, you can also create dithered images with only 1 color and a transparent background

#### Batch Processing
- **Multiple images**: Process multiple images with the same dithering settings
- **Format support**: PNG, JPG, WEBP, BMP input formats
- **High quality output**: Lossless PNG export by default

#### Dithering Pattern Editor
- **Visual editor**: Intuitive dithering pattern creation and editing
- **Multi-level patterns**: Support for complex patterns up to 10 levels (tiles)
- **Pattern library**: Save and organize custom patterns

#### Custom Presets
- Save your favorite dithering configurations in the app for future use

### Technical Specifications

#### System Requirements
- **Operating system**: Windows 10+, macOS 10.15+
- **Memory**: 4GB RAM minimum, 8GB recommended
- **Storage**: Mac: ~550mb / Windows: ~140mb available space
- **Graphics**: Hardware acceleration recommended for large images, otherwise integrated graphics is fine

#### File Support
- **Input formats**: PNG, JPG, JPEG, WEBP, BMP, GIF (no animation support for gifs though)
- **Output formats**: PNG
- **Maximum image size**: images larger than 2000px in width will be downscaled to preserve performance

### Support

- **Documentation**: User guide integrated in the app in modal form
- **General instructions**: Quick start PDF guide included
- **Updates**: Update checker in the app (Help menu)

---

**Note**: This changelog will be updated with each new release. In the app, go to Help > Check for Updates for notifications of new versions.
