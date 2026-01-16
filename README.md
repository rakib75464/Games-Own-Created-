# Games-Own-Created-
Mini Shooter - Single or Two Player
A fast-paced, retro-style space shooter game built with HTML5, CSS3, and vanilla JavaScript. Choose between single-player survival mode or competitive two-player battles in this compact, responsive arcade experience.

🎮 Game Modes
Single Player
Survive against endless waves of enemies

Destroy enemies to earn points

Avoid collisions to preserve lives

Enemies become faster and spawn more frequently as your score increases

Two Players
Competitive battle between Blue (bottom) and Red (top) players

Shoot each other to reduce opponent's lives

First player to lose all lives loses the game

Each hit on opponent awards points

🕹️ Controls
Single Player Mode
Blue Player (Bottom):

Move: Arrow Left / Arrow Right or A / D

Shoot: Space or W

Mobile: Use on-screen buttons (◀ ● ▶)

Two Player Mode
Blue Player (Bottom):

Move: Arrow Left / Arrow Right

Shoot: Space

Mobile: Use on-screen buttons (◀ ● ▶)

Red Player (Top):

Move: A / D

Shoot: W

Mobile Touch Controls
Left/Right arrows for movement

Central button for shooting

Tap anywhere on screen for quick shooting (alternative)

🎯 Game Features
Visual Design
Neon cyberpunk aesthetic with cyan/red color scheme

Animated starfield background

Glowing particle effects for explosions

Smooth animations and visual feedback

Fully responsive design (desktop & mobile)

Audio Experience
Ambient futuristic background music

Sound effects for:

Shooting

Enemy explosions

Player hits

Game over states

Game Mechanics
Progressive difficulty (single player)

Score tracking

Lives system (3 per player)

Cooldown-based shooting

Particle explosion effects

Collision detection

🚀 How to Run
Option 1: Direct Browser
Download Try.html

Open in any modern web browser (Chrome, Firefox, Edge, Safari)

No installation required

Option 2: Live Hosting
Upload Try.html to any web server

Access via URL

Share link with friends for multiplayer

📱 Compatibility
Desktop: Chrome 60+, Firefox 55+, Safari 11+, Edge 79+

Mobile: iOS Safari 11+, Chrome for Android 67+

Screen Size: Optimized for 480px width (scales to any screen)

Input: Keyboard, touch, mouse, and gamepad support

🛠️ Technical Details
Built With
HTML5 Canvas for rendering

Vanilla JavaScript (no frameworks)

CSS3 for UI and animations

Web Audio API for sound

Performance
Fixed 360×640 canvas resolution

60 FPS target

Efficient object pooling

Minimal DOM manipulation

External Assets
Background music from Pixabay

Sound effects from Mixkit

All assets loaded via CDN

🎨 Code Structure
javascript
// Core components:
- Game loop (requestAnimationFrame)
- Player objects (Blue/Red)
- Bullet system
- Enemy AI (single player)
- Collision detection
- Particle system
- State management
- Input handlers (keyboard/touch)
📊 Scoring System
Single Player
Small enemy: 10 points

Medium enemy: 20 points

Large enemy: 30 points

Two Player
Hit opponent: 20 points

Win game: 100 points bonus

🔧 Future Enhancements
Potential features for future versions:

Power-up system

Different enemy types

Boss battles

Local high score tracking

More visual effects

Difficulty settings

Controller support

Online multiplayer

📝 Notes
Game requires internet connection for audio assets (first load)

Mobile browsers may require user interaction to play audio

Best experienced in full-screen mode on mobile devices

For optimal performance, close other tabs when playing

👨‍💻 Development
File Structure
text
MiniShooter/
├── Try.html          # Main game file
└── README.md         # This documentation
Modifying the Game
Edit Try.html with any text editor

Adjust game constants in JavaScript section

Modify colors in CSS <style> block

Replace audio URLs with custom sounds

📄 License
Free to use, modify, and distribute. Credit to original creator appreciated.

🙏 Credits
Game design & development: [Your Name]

Background music: Pixabay

Sound effects: Mixkit

Inspired by classic arcade shooters

Enjoy the game! 🚀💥

For issues or suggestions, please check the code comments in Try.html for configuration options.
