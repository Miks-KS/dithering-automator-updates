# D1TH3R1NG 4UTOM4TOR - Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2024-01-15

### Initial Release

Welcome to D1TH3R1NG 4UTOM4TOR! This is the first release of this image dithering application.

### Key Features

#### Core Dithering Engine
- **Advanced Algorithm Support**: Floyd-Steinberg, Atkinson, Burkes, Sierra, and more
- **Ordered Dithering**: Bayer matrices (2x2, 4x4, 8x8, 16x16), blue noise, halftone patterns
- **Custom Pattern Support**: Create and edit your own dithering patterns

#### User Interface
- **Multi-Scale UI**: Support for 100%, 125%, 150%, and 200% scaling (for high DPI monitors)
- **Real-Time Preview**: Instant preview of dithering effects
- **Drag & Drop**: Simple image loading with validation

#### Color Management
- **Custom Palettes**: Create and manage unlimited color palettes
- **Color Presets**: Built-in presets + option to create your own presets
- **Color Extraction**: Automatic palette generation from images

#### Batch Processing
- **Multiple Images**: Process multiple images with the same dithering settings
- **Format Support**: PNG, JPG, WEBP, BMP input formats
- **High-Quality Output**: Lossless PNG export by default

#### Pattern Editor
- **Visual Editor**: Intuitive dithering pattern creation and editing
- **Multi-Level Patterns**: Support for complex patterns up to 10 levels (tiles)
- **Pattern Library**: Save and organize custom patterns

### Technical Specifications

#### System Requirements
- **Operating System**: Windows 10+, macOS 10.14+
- **Memory**: 4GB RAM minimum, 8GB recommended
- **Storage**: Approx. 550MB available space
- **Graphics**: Hardware acceleration recommended for large images, otherwise integrated graphics is fine

#### File Support
- **Input Formats**: PNG, JPG, JPEG, WEBP, BMP, GIF (no animation support for gifs though)
- **Output Formats**: PNG
- **Maximum Image Size**: images larger than 2000px in width will be downscaled to preserve performance

### Documentation

- **User Guide**: Comprehensive documentation included in the app

### Support

- **Email**: contact@miksks.com
- **Documentation**: Built-in help system
- **Updates**: Update checker in the app

---

**Note**: This changelog will be updated with each new release. Check the app's update system for notifications of new versions.
