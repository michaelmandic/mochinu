# 🍡 Mochinu

A soft and colorful color palette inspired by mochi desserts. Perfect for creating gentle, playful, and inviting user interfaces.

## 🎨 Color Palette

| Color | Hex | RGB | Preview |
|-------|-----|-----|---------|
| **Mochi Pink** | `#FFB3D9` | `255, 179, 217` | ![#FFB3D9](https://via.placeholder.com/100x30/FFB3D9/FFB3D9.png) |
| **Mochi Purple** | `#D4BFFF` | `212, 191, 255` | ![#D4BFFF](https://via.placeholder.com/100x30/D4BFFF/D4BFFF.png) |
| **Mochi Blue** | `#B3D9FF` | `179, 217, 255` | ![#B3D9FF](https://via.placeholder.com/100x30/B3D9FF/B3D9FF.png) |
| **Mochi Green** | `#B8E6B8` | `184, 230, 184` | ![#B8E6B8](https://via.placeholder.com/100x30/B8E6B8/B8E6B8.png) |
| **Mochi Yellow** | `#FFF5B3` | `255, 245, 179` | ![#FFF5B3](https://via.placeholder.com/100x30/FFF5B3/FFF5B3.png) |
| **Mochi Orange** | `#FFCCB3` | `255, 204, 179` | ![#FFCCB3](https://via.placeholder.com/100x30/FFCCB3/FFCCB3.png) |
| **Mochi Red** | `#FFB3B3` | `255, 179, 179` | ![#FFB3B3](https://via.placeholder.com/100x30/FFB3B3/FFB3B3.png) |
| **Mochi Cream** | `#FFF9E6` | `255, 249, 230` | ![#FFF9E6](https://via.placeholder.com/100x30/FFF9E6/FFF9E6.png) |
| **Mochi Brown** | `#E6D4C4` | `230, 212, 196` | ![#E6D4C4](https://via.placeholder.com/100x30/E6D4C4/E6D4C4.png) |
| **Mochi Gray** | `#E0E0E0` | `224, 224, 224` | ![#E0E0E0](https://via.placeholder.com/100x30/E0E0E0/E0E0E0.png) |

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
  background-color: var(--mochinu-pink);
  color: var(--mochinu-purple);
}
```

### SCSS Variables
```scss
@import 'colors.scss';

.my-element {
  background-color: $mochinu-pink;
  color: $mochinu-purple;
}
```

### JSON
```javascript
import colors from './colors.json';

console.log(colors.colors.pink.hex); // #FFB3D9
```

### JavaScript/TypeScript
```javascript
fetch('colors.json')
  .then(response => response.json())
  .then(palette => {
    // Use the colors
    document.body.style.backgroundColor = palette.colors.pink.hex;
  });
```

## 🎭 Preview

Open `index.html` in your browser to see an interactive preview of all colors. Click on any color card to copy its hex code to your clipboard.

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

Created by Michael Mandic with love for soft, colorful designs.
