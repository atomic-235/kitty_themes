# Kitty Themes 🐱

A collection of beautiful themes for the [kitty](https://sw.kovidgoyal.net/kitty/) terminal emulator, inspired by the popular Monokai color scheme.

## Themes

### Kittykai Ristretto
A warm, coffee-inspired theme with muted tones and good contrast.

![Kittykai Ristretto](https://raw.githubusercontent.com/atomic-235/kitty_themes/main/screenshots/kittykai-ristretto.png)

**Preview Colors:**
- Background: `#2C2525` (Dark brown)
- Foreground: `#FFF8F9` (Warm white)
- Cursor: `#FFF8F9` (Warm white)
- ANSI Colors:
  - Black: `#2C2525` / `#766d6d`
  - Red: `#fd6883` / `#f92672`
  - Green: `#adda78` / `#a6e22e`
  - Yellow: `#f9cc6c` / `#e6db74`
  - Blue: `#85dacc` / `#66d9ef`
  - Magenta: `#a8a9eb` / `#ae81ff`
  - Cyan: `#a1efe4` / `#85dacc`
  - White: `#FFF8F9` / `#ffffff`

## Installation

1. Clone this repository:
```bash
git clone https://github.com/atomic-235/kitty_themes.git
cd kitty_themes
```

2. Copy the theme file to your kitty configuration directory:
```bash
cp "themes/Kittykai Ristretto.conf" ~/.config/kitty/
```

3. Add the following line to your `~/.config/kitty/kitty.conf`:
```
include Kittykai\ Ristretto.conf
```

4. Reload kitty configuration:
```
kitty @ reload-config
```

Or use the kitty theme manager:
```bash
kitty +kitten themes --reload-in=all Kittykai\ Ristretto
```

## Usage

To switch between installed themes, you can use:
```bash
# List available themes
kitty +kitten themes

# Set a theme
kitty +kitten themes --reload-in=all <theme-name>
```

## Contributing

Contributions are welcome! Please feel free to submit new themes or improvements to existing ones.

### Adding a New Theme

1. Create a new `.conf` file in the `themes/` directory
2. Follow the naming convention: `Theme Name.conf`
3. Include a screenshot in the `screenshots/` directory
4. Update this README with your theme's information

### Theme Guidelines

- Use descriptive, creative names for themes
- Ensure good contrast and readability
- Include all 16 ANSI colors plus cursor, selection, and background colors
- Consider adding tab bar and window border colors for a complete look
- Test the theme across different programming languages and file types

## Screenshots

Screenshots help users preview themes before installation. Please include:
- Terminal with code samples (multiple languages if possible)
- Show tab bar and window borders
- Demonstrate cursor and selection colors

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to the kitty team for creating an excellent terminal emulator
- Inspired by various popular color schemes and themes in the terminal community
- Special thanks to all contributors who help make this collection better

## Related Projects

- [kitty](https://github.com/kovidgoyal/kitty) - The fast, feature-rich, GPU based terminal emulator
- [base16-kitty](https://github.com/kdrag0n/base16-kitty) - Base16 themes for kitty
- [awesome-kitty](https://github.com/kovidgoyal/awesome-kitty) - A curated list of awesome kitty-related resources

---

Made with ❤️ for the terminal community

Inspired by the classic Monokai color scheme