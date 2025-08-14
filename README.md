# 🥑 mojicado

> **treat yourself an emoji wallpaper**

A beautiful, interactive emoji wallpaper generator built with vanilla JavaScript. Create stunning wallpapers using colorful emojis and various geometric patterns.

## ✨ Features

- **🎨 Multiple Pattern Styles**: Grid, Diamonds, Hexes, Spirals, Bubbles, Stacks, and more
- **😊 Customizable Emojis**: Choose your favorite emojis or generate random ones
- **🌈 Beautiful Backgrounds**: Solid colors and gradients with a random color generator
- **📱 Responsive Design**: Works perfectly on all devices and screen sizes
- **⚡ Real-time Preview**: See changes instantly as you customize
- **💾 Download & Share**: Save your wallpapers and share links with others
- **🎯 Multiple Sizes**: Various preset sizes for different use cases

## 🚀 Live Demo

Visit the live application: [mojicado](https://your-domain.com)

## 🛠️ Technologies

- **Vanilla JavaScript (ES6+)** - No frameworks, pure performance
- **HTML5 Canvas** - High-quality rendering and image generation
- **CSS3** - Modern design with iOS-style aesthetics
- **Runes.js** - Geometric pattern generation library

## 📖 Usage

1. **Choose Pattern**: Select from various geometric patterns
2. **Pick Emojis**: Use the emoji picker or generate random ones
3. **Customize Colors**: Set background colors or use the random generator
4. **Adjust Settings**: Modify scale, arrangement, and size
5. **Download**: Save your creation or copy the shareable link

## 🎨 Pattern Styles

- **Grid** - Clean, organized emoji grid
- **Diamonds** - Diamond-shaped arrangements
- **Hexes** - Hexagonal patterns
- **Spirals** - Spiral formations
- **Bubbles** - Bubble-like clusters
- **Stacks** - Layered arrangements
- **Sprinkle** - Random scattered placement

## 🎯 Size Options

- **This Screen** - Perfect for your current device
- **This Page** - Full page dimensions
- **Cover Image** - 1500x500 for social media
- **Virtual Background** - 1920x1080 for video calls

## 🔧 Development

### Prerequisites

- Modern web browser with ES6+ support
- No build tools required

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mojicado.git
   cd mojicado
   ```

2. Open `index.html` in your browser or serve locally:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

3. Start customizing and creating!

### Project Structure

```
mojicado/
├── index.html          # Main application
├── style.css           # Styles and animations
├── script.js           # Core functionality
├── runes.js            # Pattern generation library
├── assets/             # Icons and favicons
└── README.md           # This file
```

## 🎨 Customization

### Adding New Patterns

The app uses the Runes.js library for pattern generation. You can extend it by adding new pattern functions to `runes.js`.

### Styling

All styles are in `style.css` using CSS custom properties for easy theming:

```css
:root {
  --primary-color: #007AFF;
  --secondary-color: #5856D6;
  --background-color: #F2F2F7;
  /* ... more variables */
}
```

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Credits

### Created by
- **@eswordert** - [Twitter](https://x.com/eswordert)

### Original Project
This project was inspired by and uses the excellent work from **[alcor](https://github.com/alcor)**:

- **GitHub**: [https://github.com/alcor/emoji-supply](https://github.com/alcor/emoji-supply)
- **Website**: [https://emoji.supply/wallpaper](https://emoji.supply/wallpaper)

### Open Source Libraries
- **Runes.js** - Geometric pattern generation
- **Canvas API** - HTML5 rendering engine

---

<div align="center">

**Made with ❤️ and lots of 🥑**

[Try it now!](https://your-domain.com)

</div>
