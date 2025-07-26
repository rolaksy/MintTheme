# MintTheme - Windows 10 Dark Theme for Linux

A comprehensive dark theme for Linux desktop environments that provides a Windows 10-inspired look and feel.

## Overview

MintTheme (also known as Windows-10-Dark) is a complete desktop theme package designed to give Linux systems a modern, dark Windows 10 aesthetic. The theme supports multiple desktop environments and provides consistent styling across different components.

## Features

- **Multi-Environment Support**: Compatible with GTK 2.0, 3.0, 3.20, 4.0, Cinnamon, and Metacity
- **Dark Theme**: Elegant dark color scheme for reduced eye strain
- **Windows 10 Styling**: Modern interface elements inspired by Windows 10 design
- **Complete Package**: Includes window decorations, controls, icons, and UI elements
- **Customizable**: CSS-based styling allows for easy modifications

## Supported Desktop Environments

- **GTK Applications**: Full support for GTK 2.0, 3.0, 3.20, and 4.0
- **Cinnamon Desktop**: Native Cinnamon theme with custom assets
- **Metacity Window Manager**: Window decoration theme
- **Icon Theme**: Additional icon set for enhanced visual consistency

## Directory Structure

```
MintTheme/
├── gtk-2.0/           # GTK 2.0 theme files
├── gtk-3.0/           # GTK 3.0 theme files and assets
├── gtk-3.20/          # GTK 3.20 specific theme files
├── gtk-4.0/           # GTK 4.0 theme files
├── cinnamon/          # Cinnamon desktop theme
├── metacity-1/        # Metacity window manager theme
├── extra-icons/       # Additional icon resources
├── index.theme        # Theme configuration file
├── metadata.json      # Theme metadata
└── LICENSE.md         # GPL v3 license
```

## Installation

### Method 1: Manual Installation

1. **Download/Clone the theme**:
   ```bash
   git clone <repository-url> MintTheme
   ```

2. **Copy to themes directory**:
   ```bash
   # For system-wide installation
   sudo cp -r MintTheme /usr/share/themes/

   # For user-specific installation
   mkdir -p ~/.themes
   cp -r MintTheme ~/.themes/
   ```

3. **Apply the theme**:
   - **GNOME/GTK**: Use GNOME Tweaks or your distribution's theme manager
   - **Cinnamon**: Go to System Settings → Themes
   - **XFCE**: Use Appearance settings
   - **KDE**: Use System Settings → Appearance

### Method 2: Using Theme Managers

Most Linux distributions provide theme managers that can install and apply themes:

- **GNOME Tweaks** (GNOME)
- **Cinnamon Settings** (Cinnamon)
- **Appearance Settings** (XFCE)
- **System Settings** (KDE)

## Configuration

### GTK Theme Settings

The theme includes configuration files for different GTK versions:

- `gtk-2.0/`: Legacy GTK 2.0 applications
- `gtk-3.0/`: Modern GTK 3.0 applications
- `gtk-3.20/`: GTK 3.20+ specific enhancements
- `gtk-4.0/`: Latest GTK 4.0 applications

### Cinnamon Theme

The Cinnamon theme includes:
- Custom panel styling
- Window decorations
- Menu themes
- Control elements
- Background assets

### Customization

To customize the theme:

1. **Edit CSS files**: Modify the CSS files in the respective directories
2. **Replace assets**: Update PNG/SVG files in the `assets/` directories
3. **Adjust colors**: Modify color values in the CSS files
4. **Test changes**: Restart your desktop environment or reload the theme

## Compatibility

- **Operating Systems**: Linux distributions with GTK/Cinnamon support
- **Desktop Environments**: GNOME, Cinnamon, XFCE, MATE, and others
- **GTK Versions**: 2.0, 3.0, 3.20, 4.0
- **Window Managers**: Metacity, Mutter, and compatible managers

## Troubleshooting

### Theme Not Appearing
- Ensure the theme is installed in the correct directory (`~/.themes/` or `/usr/share/themes/`)
- Check that your desktop environment supports the theme format
- Restart your desktop environment after installation

### Incomplete Styling
- Verify all theme components are present
- Check for missing dependencies (GTK versions, icon themes)
- Ensure proper file permissions

### Performance Issues
- Some older systems may experience slower rendering with complex themes
- Consider using lighter theme variants if available

## Contributing

To contribute to this theme:

1. Fork the repository
2. Make your changes
3. Test on multiple desktop environments
4. Submit a pull request with detailed descriptions

## License

This theme is licensed under the GNU General Public License v3.0. See [LICENSE.md](LICENSE.md) for the full license text.

## Credits

- Theme design inspired by Windows 10 interface
- Built for Linux desktop environments
- Community contributions welcome

## Support

For issues, suggestions, or contributions:
- Report bugs through the issue tracker
- Join community discussions
- Check documentation for common solutions

---

**Note**: This theme is designed to provide a Windows 10-like experience on Linux systems while maintaining compatibility with native Linux desktop environments and applications.
