# 🚀 Space Shooter - Pygame Edition

A classic arcade-style space shooter game built with Python and Pygame. Survive as long as possible while dodging rotating meteors and blasting them out of your path! 


<img width="1594" height="931" alt="{A5ED6D04-CA41-4F7F-8A23-3F6425FF14FC}" src="https://github.com/user-attachments/assets/99e840b0-9aa2-44a4-a073-c79d3af33db0" />



### Core Gameplay
- **Smooth player movement** with arrow key controls
- **Laser shooting mechanics** with cooldown system
- **Rotating meteors** with randomized spawn patterns
- **Collision detection** using pygame masks for pixel-perfect accuracy
- **Animated explosions** when meteors are destroyed
- **Real-time scoring** based on survival time

### Technical Features
- **Object-oriented design** with sprite classes
- **Delta time movement** for smooth 60 FPS gameplay
- **Sound effects** and background music
- **Particle effects** with animated explosion sequences
- **Optimized performance** with automatic sprite cleanup

## 🎯 How to Play

**Objective:** Survive as long as possible by avoiding meteors and shooting them down!

- Navigate your spaceship through a meteor storm
- Shoot lasers to destroy incoming meteors
- Each destroyed meteor triggers an explosion animation
- Your score increases based on survival time
- Game ends when your ship collides with a meteor

## 🕹️ Controls

| Key | Action |
|-----|---------|
| `↑` | Move Up |
| `↓` | Move Down |
| `←` | Move Left |
| `→` | Move Right |
| `SPACE` | Shoot Laser |
| `ESC` | Quit Game |

## 📋 Requirements

- **Python 3.7+**
- **Pygame 2.0+**

## 🛠️ Installation & Setup

1. **Clone or download** this repository
2. **Install pygame:**
   ```bash
   pip install pygame
   ```
3. **Ensure you have the following file structure:**
   ```
   space-shooter/
   ├── main.py
   ├── images/
   │   ├── player.png
   │   ├── star.png
   │   ├── meteor.png
   │   ├── laser.png
   │   ├── Oxanium-Bold.ttf
   │   └── explosion/
   │       ├── 0.png
   │       ├── 1.png
   │       └── ... (20 explosion frames)
   └── audio/
       ├── laser.wav
       ├── explosion.wav
       └── game_music.wav
   ```

4. **Run the game:**
   ```bash
   python main.py
   ```

## 🎨 Assets Required

### Images
- `player.png` - Player spaceship sprite
- `meteor.png` - Meteor sprite (gets rotated dynamically)
- `laser.png` - Laser projectile sprite
- `star.png` - Background star decoration
- `explosion/0.png` to `explosion/20.png` - 21 explosion animation frames
- `Oxanium-Bold.ttf` - Game font

### Audio
- `laser.wav` - Laser shooting sound effect
- `explosion.wav` - Explosion sound effect
- `game_music.wav` - Background music (loops continuously)
- 
### Scoring
- Score = Time Survived ÷ 100
- Displayed in real-time at bottom of screen
- Styled with background rectangle for visibility

### Performance
- Automatic cleanup of off-screen sprites
- Efficient collision detection using sprite groups
- 60 FPS target with delta time compensation

## 📝 License

This project is open source and available for educational purposes.
