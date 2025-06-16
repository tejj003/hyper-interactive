# Nexus - Interactive Data Visualization

A stunning, high-performance interactive particle system visualization with real-time controls and dynamic effects. Experience a mesmerizing display of interconnected particles that respond to your mouse movements and interactions.

![Nexus Preview](preview.png)

## 🌟 Features

### Visual Effects
- **Dynamic Particle System**: Hundreds of animated particles with fluid motion
- **Real-time Connections**: Particles connect when within range, creating a network effect
- **Mouse Interaction**: Particles are attracted to your cursor with adjustable gravity
- **Particle Trails**: Smooth trails follow each particle's movement
- **Glow Effects**: Energy-based glow system for enhanced visuals
- **Click Explosions**: Click anywhere to create particle explosions

### UI Controls
- **Particle Density** (100-2000): Control the number of particles
- **Flow Velocity** (0.1-5): Adjust particle movement speed
- **Connection Range** (50-200): Set the maximum distance for particle connections
- **Gravity Force** (0-2): Control cursor attraction strength
- **Energy Field** (0-100): Adjust the particle field effects

### Themes
- **Default**: Green primary with pink secondary colors
- **Neon**: Vibrant magenta and cyan
- **Ocean**: Cool blues and aqua tones
- **Sunset**: Warm oranges and reds

### Presets
- **Calm**: Gentle, slow-moving particles for a relaxing experience
- **Dynamic**: Balanced settings for active visualization
- **Chaos**: High-energy, fast-moving particle storm
- **Minimal**: Fewer particles with subtle movements

### Additional Features
- **Wave Visualizer**: Bottom panel shows audio-like wave animations
- **Statistics Panel**: Real-time FPS, particle count, connections, and energy monitoring
- **Minimizable Panels**: Click minimize buttons to hide/show control panels
- **Persistent Settings**: Panel states are saved in localStorage
- **Keyboard Shortcuts**:
  - `Space`: Pause/Resume animation
  - `R`: Reset particles
  - `C`: Clear all particles

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No dependencies or build process required!

### Installation
1. Clone or download the repository
2. Open `index.html` in your web browser
3. That's it! No installation needed

### Usage
1. Move your mouse to interact with particles
2. Click anywhere on the canvas to create explosions
3. Use the control panel to adjust visualization parameters
4. Switch themes using the theme buttons
5. Try different presets for varied experiences
6. Minimize panels by clicking the arrow button

## 🎮 Controls Guide

### Sliders
- **Particle Density**: More particles = more connections but higher performance impact
- **Flow Velocity**: Higher values create faster, more chaotic movement
- **Connection Range**: Larger ranges create more interconnected networks
- **Gravity Force**: Stronger gravity makes particles follow your cursor more closely
- **Energy Field**: Adds wave-like motion to particle movement

### Performance
The visualization automatically detects your device capabilities and adjusts:
- **High Performance**: Full effects with trails and glow
- **Medium Performance**: Balanced effects
- **Low Performance**: Reduced effects for smooth animation

## 🛠️ Technical Details

### Technologies Used
- **HTML5 Canvas**: Hardware-accelerated 2D rendering
- **Vanilla JavaScript**: No frameworks, pure performance
- **CSS3**: Glassmorphism UI with backdrop filters
- **ES6+**: Modern JavaScript features

### Performance Optimizations
- Spatial grid system for efficient connection calculations
- Object pooling for explosion particles
- Dynamic quality adjustment based on FPS
- RequestAnimationFrame for smooth 60fps animation
- Efficient particle culling and boundary wrapping

### Browser Compatibility
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 📱 Mobile Support

The visualization is responsive and works on mobile devices with:
- Touch interaction support
- Adjusted UI layout for smaller screens
- Hidden theme/preset panels on mobile
- Performance optimizations for mobile GPUs

## 🎨 Customization

You can easily customize the visualization by modifying:
- Color schemes in the CSS variables
- Particle behaviors in the JavaScript configuration
- UI styling with the glassmorphism effects
- Add new themes or presets

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Share your custom themes

## 🙏 Acknowledgments

- Inspired by particle system visualizations
- Built with modern web technologies
- Designed for both aesthetics and performance

---

**Enjoy the mesmerizing world of Nexus!** ✨
