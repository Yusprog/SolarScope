
# SolarScope: Solar System Simulation 🌌

An interactive 3D solar system simulation for exploring planetary orbits, sizes, and gravitational physics. This project allows users to explore planetary sizes and orbital mechanics, observe realistic shadow effects between celestial bodies, and experience extreme gravitational phenomena through our black hole simulation. Read the following guide to learn how to navigate and interact with our solar system. 

<img width="395" alt="SolarScope Screenshot" src="https://github.com/user-attachments/assets/c616b2cc-58c1-49d7-ad51-a5721c6858a6" />
<img width="395" alt="SolarScope Screenshot" src="https://github.com/user-attachments/assets/a3be33e3-deb8-4a23-a171-ebccb59ed759" />
<img width="395" alt="SolarScope Screenshot" src="https://github.com/Yusprog/SolarScope/blob/12a1273a1e12447fc33565c45b2dae0621b27bfc/textures/Sc1.png" />
 <img width="395" alt="SolarScope Screenshot" src="https://github.com/Yusprog/SolarScope/blob/12a1273a1e12447fc33565c45b2dae0621b27bfc/textures/sc2.png" />


## Features

**Exploration & Learning:**
- Fly through space in first/third-person view as a rubber duck 🦆
- Planet selection mode with detailed info panels
- Size comparison mode - align planets to see relative scales
- Watch planets cast realistic shadows on each other
- Complete solar system with all planets, moon, and comet

**Physics & Effects:**
- Time control - speed up (10x), reverse, or pause orbital motion
- Black hole simulation with gravitational collapse
- Phong lighting model with sun as light source
- Comet with elliptical orbit and dynamic particle trails
- Atmospheric glow effects and 360° space skybox
- Hierarchical animation (moon orbits Earth, planets orbit sun)

**Technical Highlights:**
- Real-time shadow rendering between celestial bodies
- Complex 3D models loaded via Assimp (duck.gltf)
- Multiple specialized shaders (celestial, skybox, UI, model rendering)
- 10+ unique planetary textures with proper UV mapping

## Controls

### Camera Movement:
- **1 & 2**: Switch between first-person and third-person view, as a rubber duck object circulating space
- **W A S D**: Move around the solar system
- **Mouse or Arrow Keys**: Look around/rotate camera
- **Shift**: Move faster through space

### Planet Selection Mode:
- **3**: Enter planet selection mode / Cycle through planets
- **4**: Exit planet selection mode (return to free camera)
- **I**: Show/hide detailed information panel for selected planet

### Time Control:
- **Space**: Pause/unpause time (all orbital movements)
- **9**: Reverse time direction (planets orbit backwards)
- **0**: Reset orbital speed to normal (1x speed)
- **+ (Plus)**: Increase orbital speed (up to 10x faster)
- **- (Minus)**: Decrease orbital speed (can go into reverse)

### Special Modes:
- **X**: Trigger black hole effect 
- **R**: Reset world to normal state (after black hole)
- **C**: Activate size comparison mode (align planets by size)

**Pro tip:** Combine modes! Use planet selection in comparison mode for detailed study.

## Libraries Used

- OpenGL 
- GLFW 3.4 
- GLM 1.0.1 
- GLEW 2.2.0 
- Assimp 6.0.2 

## Contributors

- Yusuf Chahal 
- Dania Houssami 
- Mohammad Alshikh
