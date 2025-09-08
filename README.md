# 🎨 Copymangle

**A comprehensive UI enhancement for [Copyparty](https://github.com/9001/copyparty)**

This project provides modern, accessible styling improvements for the Copyparty file sharing web interface, focusing on better usability, visual appeal, and user experience.

## ✨ Features

- 🎯 **Modern Design**: Clean, contemporary interface with improved typography and spacing
- 🎨 **Multiple Themes**: Support for various color schemes and visual styles
- ♿ **Accessibility**: Enhanced readability with better contrast and font choices
- 📱 **Responsive**: Optimized for different screen sizes and devices
- ⚡ **Performance**: Optimized CSS with efficient selectors and minimal redundancy
- 🔧 **Easy Integration**: Simple one-line configuration to apply the styles

## 🚀 Quick Start

### Option 1: Direct Link (Recommended)

Add this to your Copyparty configuration:

**Command Line:**
```bash
copyparty --html-head='<link rel="stylesheet" href="https://blade04208.github.io/copymangle/main.css">'
```

**YAML Configuration:**
```yaml
[global]
html-head: <link rel="stylesheet" href="https://blade04208.github.io/copymangle/main.css">
```

### Option 2: Local Installation

For development or offline use:

```bash
# Clone the repository
git clone https://github.com/blade04208/copymangle.git
cd copymangle

# Configure Copyparty to use local CSS
copyparty --html-head='<link rel="stylesheet" href="/path/to/copymangle/main.css">'
```

> 💡 **Pro Tip**: The local installation automatically reloads CSS changes on page refresh, perfect for development!

## 🎯 What's Improved

### Visual Enhancements
- **Typography**: Atkinson Hyperlegible font for better readability
- **Color Scheme**: Carefully chosen color palette with proper contrast ratios
- **Layout**: Improved spacing, padding, and visual hierarchy
- **Interactive Elements**: Enhanced hover states and transitions

### User Experience
- **File Management**: Better visual distinction between file types and states
- **Navigation**: Improved tree navigation and breadcrumb styling
- **Forms**: Enhanced input styling and validation feedback
- **Notifications**: Better toast notifications and modal dialogs

### Technical Improvements
- **CSS Variables**: Extensive use of CSS custom properties for easy theming
- **Performance**: Optimized selectors and reduced specificity conflicts
- **Browser Support**: Fallbacks for older browsers where possible
- **Maintainability**: Well-organized CSS with clear section comments

## 🔧 Configuration

### Available Themes

The stylesheet includes several built-in theme variations:

- **Default**: Purple/magenta accent theme
- **Light Theme** (`html.y`): Clean light color scheme
- **Dark Variations**: Multiple dark theme options
- **High Contrast**: Enhanced accessibility options
- **Monochrome**: Minimal color schemes

### Customizing

You can override any CSS variable to customize the appearance:

```css
:root {
  --a: #your-accent-color;
  --bg: #your-background-color;
  --fg: #your-text-color;
}
```

## 📋 Requirements

- **Copyparty**: Compatible with all recent versions
- **Browser Support**:
  - Chrome/Edge 88+
  - Firefox 78+
  - Safari 14+
  - Limited support for older browsers

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-improvement`
3. Make your changes and test with Copyparty
4. Submit a pull request

### Development Setup

```bash
# Clone and setup
git clone https://github.com/blade04208/copymangle.git
cd copymangle

# Start Copyparty with local CSS for testing
copyparty --html-head='<link rel="stylesheet" href="./main.css">' [other-options]
```

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Original Copyparty project by [9001](https://github.com/9001)
- Font: [Atkinson Hyperlegible](https://github.com/googlefonts/atkinson-hyperlegible) by Braille Institute
- Community contributions and feedback

---

**Made with ❤️ for the Copyparty community**