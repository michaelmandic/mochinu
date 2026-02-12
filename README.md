# 🍡 Mochinu

A color palette template. Replace the placeholder colors with your own palette.

## 🎨 Color Palette

Replace the colors in `colors.json`, `colors.css`, and `colors.scss` with your actual color values.

## 📦 Installation

### NPM (Coming Soon)
```bash
npm install mochinu
```

### Manual Installation
Download the color files directly from this repository:
- `colors.json` - JSON format
- `colors.css` - CSS custom properties
- `colors.scss` - SCSS variables

## 🚀 Usage

### CSS Custom Properties
```html
<link rel="stylesheet" href="colors.css">
```

```css
.my-element {
  background-color: var(--mochinu-color1);
  color: var(--mochinu-color2);
}
```

### SCSS Variables
```scss
@import 'colors.scss';

.my-element {
  background-color: $mochinu-color1;
  color: $mochinu-color2;
}
```

### JSON
```javascript
import colors from './colors.json';

console.log(colors.colors.color1.hex); // Access color values
```

### JavaScript/TypeScript
```javascript
fetch('colors.json')
  .then(response => response.json())
  .then(palette => {
    // Use the colors
    document.body.style.backgroundColor = palette.colors.color1.hex;
  });
```

## 💡 Use Cases

- Web design and development
- UI/UX design systems
- Mobile app interfaces
- Graphic design projects
- Branding and marketing materials
- Data visualization
- Presentation templates

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🌟 Credits

Created by Michael Mandic.
