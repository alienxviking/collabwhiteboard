# Interactive Whiteboard

A lightweight, browser-based drawing application built with vanilla JavaScript, HTML5 Canvas, and CSS. This whiteboard provides a simple yet powerful interface for digital drawing and sketching.

## Features

### Drawing Tools
- ✏️ Pencil Tool: Free-hand drawing
- ⬜ Rectangle Tool: Draw rectangular shapes
- ⭕ Circle Tool: Draw circular shapes
- 🧹 Eraser Tool: Erase portions of your drawing
- ↩️ Undo: Revert last action (latest version)
- ↪️ Redo: Restore previously undone action (latest version)

### Customization
- 🎨 Color Picker: Choose any color for drawing
- 📏 Line Width: Adjust stroke thickness (1-20px)
- 💾 Save Feature: Export your drawing as PNG
- 🗑️ Clear Canvas: Start fresh with a clean slate

## Usage

### Basic Controls
- Click and drag to draw
- Select tools from the toolbar
- Use the color picker to change drawing color
- Adjust line width using the slider
- Click "Save" to download your drawing
- Click "Clear" to reset the canvas

### Tool-Specific Usage
1. **Pencil Tool**
   - Click and drag for free-hand drawing
   - Best for detailed sketching

2. **Rectangle Tool**
   - Click and drag to define rectangle dimensions
   - Release to complete the shape

3. **Circle Tool**
   - Click at the center point
   - Drag to define radius
   - Release to complete the circle

4. **Eraser Tool**
   - Click and drag over areas to erase
   - Size adjustable using the width slider

## Technical Details

### Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

### Canvas Specifications
- Default canvas size: 800x600 pixels
- Responsive scaling for different screen sizes
- High-quality rendering with anti-aliasing

### Performance Features
- Optimized for smooth drawing
- Buffer system for shape rendering
- Real-time coordinate tracking
- Memory-efficient state management

## Project Structure
```
interactive-whiteboard/
│
├── index.html          # Main HTML file with embedded CSS and JavaScript
├── README.md          # This documentation file
└── screenshots/       # (Optional) Interface screenshots
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Development

### To Modify Styles
- CSS styles are embedded in the `<style>` section of `index.html`
- Main styling variables:
  - Background color: `#f0f2f5`
  - Tool button color: `#e9ecef`
  - Active tool color: `#4dabf7`

### To Add New Tools
1. Add new button in the toolbar:
```html
<button class="tool-btn" data-tool="newTool">New Tool</button>
```

2. Add tool logic in the draw function:
```javascript
case 'newTool':
    // Add your tool's drawing logic here
    break;
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Built with vanilla JavaScript
- Uses HTML5 Canvas API
- Inspired by classic paint programs

## Version History

### Version 1.0.0
- Initial release with basic drawing tools

### Version 1.1.0
- Added undo/redo functionality
- Improved tool organization
- Enhanced state management

## Support

For support, please open an issue in the GitHub repository or contact the maintainers directly.
