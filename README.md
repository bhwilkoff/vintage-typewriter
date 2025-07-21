# 🖨️ Vintage Typewriter

A fully functional, immersive vintage typewriter simulator built with pure HTML, CSS, and JavaScript. Experience the nostalgic charm of typewriting with authentic sounds, visual effects, and mechanical behaviors.

## 🚀 [Live Demo](https://bhwilkoff.github.io/vintage-typewriter/vintage_typewriter.html)

## ✨ Features

### 🎵 **Authentic Audio Experience**
- **Realistic keystroke sounds** - Each key produces a unique, lower-pitched mechanical sound
- **Mechanical backspace thud** - Non-resonant, authentic lever sound
- **Multi-harmonic warning bell** - Beautiful bell that rings 5 characters before line end
- **Carriage return clunk** - Satisfying mechanical sound when hitting margins
- **Variable volume** - Sounds increase in intensity when approaching margins
- **Persistent audio** - Sounds never disappear, even after clearing documents

### ⌨️ **Typewriter Mechanics**
- **Carriage return mode** - Prevents typing beyond line margins (toggle on/off)
- **Responsive line length** - Automatically adapts to screen width
- **Margin indicator** - Visual red line appears when at maximum line length
- **Type bar animations** - Watch mechanical type bars strike with each keypress
- **Shift key functionality** - Proper uppercase and symbol typing

### 🎨 **Visual Design**
- **5 color themes** - Desert Sand, Alpine Blue, Sapphire Gray, Seafoam Green, Coral Pink
- **Animated type bars** - 45+ individual type bars with realistic 3D movement
- **Vintage paper area** - Clean, paper-like typing surface with shadows
- **Responsive design** - Works beautifully on desktop, tablet, and mobile
- **Smooth scrolling** - Smart auto-scroll that only activates when needed

### 📄 **Document Management**
- **Save documents** - Download your work as plain text files
- **New document** - Clear workspace with confirmation dialog
- **Smart scrolling** - Always keeps your typing visible
- **Content preservation** - No unexpected jumping or lost text

### 🖱️ **Input Methods**
- **Physical keyboard** - Full support for hardware keyboards
- **On-screen keyboard** - Click the vintage keys for typing
- **Mobile support** - Touch-friendly interface for mobile devices
- **Keyboard shortcuts** - Page Up/Down, End, Ctrl+Arrow for navigation

## ⌨️ How to Use

1. **Start typing immediately** - Use your keyboard or click the on-screen keys
2. **Listen for the warning bell** - Signals when you're 5 characters from line end
3. **Toggle carriage return mode** - Use the ↵ button to enable/disable line limits
4. **Adjust sound** - Use the ♪ button to toggle typewriter sounds
5. **Change themes** - Click the colored buttons on the left to switch keyboard themes
6. **Save your work** - Click the "S" button to download your document
7. **Start fresh** - Click the "N" button to begin a new document

## 🛠️ Technical Details

- **Pure vanilla JavaScript** - No frameworks or dependencies
- **Web Audio API** - Real-time sound synthesis for authentic typewriter audio
- **CSS Grid & Flexbox** - Modern responsive layout
- **CSS Animations** - Smooth 3D transformations for type bars
- **Local file downloads** - Uses Blob API for document saving
- **Mobile responsive** - Adaptive design for all screen sizes

## 📱 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 14+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

*Note: Audio features require user interaction to comply with browser autoplay policies.*

## 🚀 Installation

### Option 1: GitHub Pages (Recommended)
Simply visit the [live demo](https://bhwilkoff.github.io/vintage-typewriter/vintage_typewriter.html) - no installation required!

### Option 2: Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/bhwilkoff/vintage-typewriter.git
   cd vintage-typewriter
   ```

2. Open in your browser:
   ```bash
   # Simply open the HTML file in any modern web browser
   open vintage_typewriter.html
   # or
   python -m http.server 8000  # For local server
   ```

### Option 3: Download and Run
1. Download the `vintage_typewriter.html` file
2. Open it in any modern web browser
3. Start typing!

## 🎨 Customization

The typewriter is highly customizable through CSS variables and JavaScript configuration:

- **Line length**: Modify `maxLineLength` calculation in JavaScript
- **Sound parameters**: Adjust gain, frequency, and duration in `playTypewriterSound()`
- **Colors**: Add new themes by extending the color picker
- **Type bar characters**: Modify the `chars` array to change available type bars

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Commit your changes**: `git commit -m 'Add amazing feature'`
4. **Push to branch**: `git push origin feature/amazing-feature`
5. **Open a Pull Request**

### Ideas for Contributions
- Additional sound profiles (electric typewriter, different mechanical types)
- More color themes
- Font selection options
- Document templates
- Export formats (PDF, RTF)
- Typing statistics
- Multiple document tabs

## 🐛 Known Issues

- Audio may require initial user interaction on some browsers
- Very long documents may impact performance on older devices
- Some mobile keyboards may interfere with the on-screen keyboard

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by classic typewriters and vintage computing
- Sound design based on real typewriter recordings and mechanical analysis
- CSS animations inspired by 3D typewriter visualizations

## 📞 Support

If you encounter any issues or have suggestions:
- 🐛 [Report bugs](https://github.com/bhwilkoff/vintage-typewriter/issues)
- 💡 [Request features](https://github.com/bhwilkoff/vintage-typewriter/issues)
- ⭐ Star the repository if you enjoyed it!

---

**Made with ❤️ for typewriter enthusiasts and nostalgia lovers everywhere.**