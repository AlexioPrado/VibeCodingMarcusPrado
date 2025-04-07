
## Development Guide

### Project Structure
```
VibeCodingMarcusPrado/
├── index.html    # Main game file with HTML, CSS, and JavaScript
└── README.md     # Documentation
```

### Development Tips
1. **Browser Dev Tools**
   - Use Chrome/Firefox DevTools (F12) to debug
   - Check Console for errors
   - Use Performance tab to monitor frame rate

2. **Performance Optimization**
   - Game uses object pooling for bullets
   - Automatic cleanup of off-screen objects
   - Collision detection optimization
   - Frame rate may drop with many objects

### Common Issues

1. **Game Lag**
   - Reduce number of active turrets
   - Clear screen of excess pellets
   - Close other browser tabs
   - Enable hardware acceleration in browser

2. **Controls Not Working**
   - Ensure browser window is focused
   - Check if keyboard layout is correct
   - Verify no browser extensions interfering

3. **Display Issues**
   - Try refreshing the page
   - Clear browser cache
   - Check zoom level (should be 100%)
   - Ensure minimum resolution requirements met

### Contributing
1. Fork the repository
2. Create feature branch
3. Make changes
4. Test thoroughly
5. Submit pull request

For major changes, please open an issue first to discuss proposed changes.

## Deployment Guide

### Local Setup
1. Download the project files:
   ```bash
   git clone https://github.com/AlexioPrado/VibeCodingMarcusPrado.git
   cd VibeCodingMarcusPrado
   ```

2. Run the game locally using one of these methods:

   **Using Python:**
   ```bash
   python -m http.server 8000
   ```
   Then open: http://localhost:8000

   **Using VS Code:**
   - Install "Live Server" extension
   - Right-click index.html
   - Select "Open with Live Server"

### Hosting Options

1. **GitHub Pages (Free)**
   - Go to repository Settings
   - Navigate to Pages section
   - Select main branch
   - Save and wait for deployment
   - Access at: https://[username].github.io/VibeCodingMarcusPrado

2. **Netlify (Free)**
   - Sign up at netlify.com
   - Connect GitHub repository
   - Select main branch
   - Deploy automatically

### System Requirements
- Modern web browser (Chrome, Firefox, Edge, Safari)
- 1024x768 minimum resolution
- Keyboard and mouse
- JavaScript enabled