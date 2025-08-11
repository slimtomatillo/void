# Void - 3D Space Mapping Platform

A **3D interactive visualization** of our solar system built with Three.js, featuring accurate planetary positioning, orbital mechanics, and real-time animations. Think "Google Earth for space" - a beautiful, immersive way to explore our cosmic neighborhood.

## Project Overview

Void is a **3D interactive solar system simulator** that provides an accurate, to-scale representation of our solar system. Users can navigate through space, observe planetary orbits in real-time, and explore detailed information about each celestial body.

## Project Structure

```
void/
├── frontend/          # 3D Three.js application
├── backend/          # Future FastAPI server (Phase 3+)
├── data/             # JSON data files
└── README.md
```

## Current Features (Phase 1 - 3D Visualization) ✅

### 🚀 **3D Solar System Visualization**
- **Fully 3D environment** using Three.js WebGL renderer
- **Accurate planetary positioning** with real astronomical distances
- **Real-time orbital animations** with correct orbital periods
- **Planetary rotation** on their axes
- **Interactive 3D camera controls** (orbit, pan, zoom)

### 🌟 **Enhanced Celestial Bodies**
- **Sun** with glowing corona effect and dynamic lighting
- **All 8 planets** with enhanced materials and atmospheric glows
- **Visual distinction** through emissive materials and atmospheric effects
- **Orbital rings** showing planetary paths with improved visibility
- **Realistic materials** and lighting effects

### 🎮 **Interactive Controls & Hover Effects**
- **Mouse navigation**: Click and drag to orbit, scroll to zoom
- **Hover effects**: **Neon green tracing rings** appear when hovering over objects
- **Info bubbles**: **Detailed metadata popups** on hover with real-time data
- **Click selection**: Click objects to select and highlight them
- **Animation speed control**: Adjust orbital and rotation speeds
- **Distance scaling**: Modify the scale of distances for better visualization
- **Size scaling**: Adjust planet sizes for better visibility
- **Camera reset**: Return to default viewing position

### 📊 **Information Display**
- **Real-time data display** for selected objects
- **Hover tooltips** with instant object information
- **Scientific accuracy**: Mass, radius, distance, orbital periods
- **Detailed descriptions** of each celestial body
- **Visual highlighting** with neon green selection rings

### 🎨 **Visual Features**
- **Dark space theme** with realistic lighting
- **Dynamic shadows** and ambient lighting
- **Atmospheric glows** around planets for better visibility
- **Enhanced sun corona** and planetary atmospheres
- **Responsive design** that works on all screen sizes
- **Smooth animations** with 60fps rendering

### 🔧 **Layer System (Future-Ready)**
- **Current layers**: Planets & Sun, Orbital Paths
- **Planned layers**: Moons & Satellites, Asteroid Belts, Annotations & Labels, Constellation Lines
- **Layer controls** ready for future implementation
- **Toggle functionality** for different visualization modes

## Technical Implementation

### **Frontend Stack**
- **Three.js r128** for 3D graphics and WebGL rendering
- **Vanilla JavaScript** for interactivity and animations
- **CSS3** for UI styling and responsive design
- **HTML5** for structure and accessibility

### **3D Graphics Features**
- **WebGL rendering** with hardware acceleration
- **Real-time shadows** and lighting calculations
- **Efficient geometry** with optimized meshes
- **Smooth camera controls** with damping and constraints
- **Hover detection** with raycasting for precise object interaction
- **Dynamic materials** with emissive properties and transparency

### **Interactive Features**
- **Raycasting system** for accurate object selection
- **Hover effects** with neon green tracing rings
- **Info bubble system** for real-time data display
- **Selection highlighting** with persistent visual feedback
- **Layer management** infrastructure for future features

### **Data Structure**
The platform uses a comprehensive JSON data structure that includes:
- **Celestial Object Properties**: Name, type, distance, radius, mass, color
- **Orbital Mechanics**: Orbital period, rotation period, inclination, eccentricity
- **Visual Properties**: Colors, materials, and lighting effects
- **Scientific Accuracy**: Real astronomical data from NASA and scientific sources

## Getting Started

### **Phase 1 (Current - 3D Visualization)**
1. Open `frontend/index.html` in a modern web browser
2. **Navigate the 3D solar system**:
   - **Left click + drag**: Orbit around the scene
   - **Right click + drag**: Pan the view
   - **Scroll wheel**: Zoom in/out
3. **Hover over objects** to see neon green tracing and info bubbles
4. **Click on planets** to select and view detailed information
5. **Use the control panel** to adjust animation speed and scales
6. **Reset camera** to return to the default view

### **Controls Guide**
- **Animation Speed**: Control how fast planets orbit and rotate
- **Distance Scale**: Adjust the scale of distances (useful for seeing outer planets)
- **Size Scale**: Modify planet sizes for better visibility
- **Reset Camera**: Return to the default viewing position

### **Interaction Guide**
- **Hover**: Move mouse over objects to see neon green tracing rings and info bubbles
- **Click**: Select objects to highlight them and show detailed information
- **Navigate**: Use mouse controls to explore the 3D space
- **Layers**: View current and future layer options (some disabled for future implementation)

## Data Sources & Accuracy

The visualization includes **scientifically accurate data**:
- **Planetary Distances**: Based on astronomical units (AU) from the Sun
- **Orbital Periods**: Real orbital periods in Earth days
- **Rotation Periods**: Actual rotation speeds of planets
- **Planetary Sizes**: Relative to actual planetary radii
- **Colors**: Based on actual planetary appearances and spectral data

## Future Enhancements

### **Phase 2: Advanced 3D Features**
- **Satellite systems** (moons, rings) - Layer system ready
- **Asteroid belts** and dwarf planets - Layer system ready
- **Spacecraft models** and trajectories
- **Constellation overlays** - Layer system ready
- **Time controls** (pause, fast-forward, reverse)

### **Phase 3: Extended Universe**
- **Nearby star systems** (Alpha Centauri, Sirius, etc.)
- **Exoplanet visualization**
- **Deep space objects** (nebulae, galaxies)
- **User-generated content** and annotations - Layer system ready

### **Phase 4: Interactive Features**
- **Measurement tools** for distances and angles
- **Trajectory planning** for space missions
- **Educational overlays** and information panels - Layer system ready
- **VR/AR support** for immersive experiences

### **Layer System Implementation**
The current layer panel shows the roadmap for future features:
- ✅ **Planets & Sun** - Currently active
- ✅ **Orbital Paths** - Currently active  
- 🔄 **Moons & Satellites** - Ready for implementation
- 🔄 **Asteroid Belts** - Ready for implementation
- 🔄 **Annotations & Labels** - Ready for implementation
- 🔄 **Constellation Lines** - Ready for implementation

## Development Tips

- **Start with 3D basics**: Focus on getting the core 3D visualization working
- **Optimize performance**: Use efficient geometries and materials
- **Test on different devices**: Ensure smooth performance on various hardware
- **Maintain scientific accuracy**: Keep data sources reliable and up-to-date
- **User experience first**: Make navigation intuitive and smooth
- **Layer architecture**: Build with future extensibility in mind

## Browser Compatibility

- **Chrome/Edge**: Full support with hardware acceleration
- **Firefox**: Full support with WebGL
- **Safari**: Full support on macOS
- **Mobile**: Responsive design with touch controls

---

**Void** - Exploring the universe in stunning 3D detail. 🚀✨

*Built with Three.js for immersive space exploration*

### 🆕 **Latest Updates**
- **Neon green hover tracing** for all celestial objects
- **Info bubbles** with real-time metadata on hover
- **Enhanced visual distinction** between objects
- **Layer system infrastructure** for future features
- **Improved atmospheric effects** and materials 