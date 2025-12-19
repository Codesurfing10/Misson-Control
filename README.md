# Mission Control - Cockpit Simulator

An interactive cockpit simulator that lets you experience different mission environments with realistic cockpit designs and controls.

## Features

### 🚀 Start Mission Button
- Click "Start Mission" to begin your journey
- Animated button with pulsing effect
- Welcome screen with mission briefing

### 🎮 Multiple Mission Environments
Switch between four unique environments:
- **🌌 SPACE**: Navigate through the cosmos with a spaceship cockpit
- **⛰️ MOUNTAINS**: Fly through mountain ranges with an F16 Raptor cockpit
- **🏜️ DESERT**: Traverse desert landscapes with an F16 Raptor cockpit
- **🌊 OCEAN**: Soar over ocean territories with a Boeing 747 cockpit

### 🛩️ Environment-Specific Cockpit Designs

#### Spaceship Cockpit (Space Missions)
- Futuristic circular viewport with blue glow
- Side consoles with tech displays
- Panel lights and indicators
- Designed for space exploration

#### F16 Raptor Cockpit (Desert & Mountain Missions)
- Military-style angular canopy frame
- Instrument gauges at the bottom panel
- Green HUD elements
- Fighter jet aesthetic

#### Boeing 747 Cockpit (Ocean Missions)
- Commercial aircraft windscreen with center post
- Wide instrument panel with multiple displays
- Primary Flight Display and Navigation Display screens
- Overhead panel indicators

### ⌨️ Arrow Key Controls
Control your vessel with keyboard arrow keys:
- **↑ Up Arrow**: Move forward or ascend (increases altitude in space/mountains)
- **↓ Down Arrow**: Move backward or descend (decreases altitude in space/mountains)
- **← Left Arrow**: Steer left
- **→ Right Arrow**: Steer right

Visual feedback is provided with:
- Arrow key indicators in the bottom-right corner
- Movement feedback messages at the top
- Real-time HUD updates

### 📊 HUD (Heads-Up Display)
- **Location Display**: Current mission environment
- **Altitude**: Height above ground/sea level
- **Velocity**: Current speed
- **Coordinates**: Position tracking
- **Time**: Current time display
- **Crosshair**: Center targeting reticle
- **Corner frames**: Tactical display borders

### 🎨 Quick Environment Switching
- Use on-screen buttons to switch environments
- Or use number keys: 1 (Space), 2 (Mountains), 3 (Desert), 4 (Ocean)
- Smooth transitions between environments
- Cockpit automatically adapts to selected environment

## How to Use

1. Open `index.html` in your web browser
2. Click the "Start Mission" button on the welcome screen
3. Select your mission environment using the on-screen buttons
4. Use arrow keys to navigate and control your vessel
5. Watch the HUD for real-time information about your mission

## Browser Compatibility
- Works on all modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design adapts to different screen sizes
- Hardware acceleration recommended for smooth animations

## Technical Details
- Pure HTML5, CSS3, and JavaScript
- Canvas-based rendering for landscapes and cockpit overlays
- Real-time animation with requestAnimationFrame
- No external dependencies required