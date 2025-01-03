# Space Invaders Game

A modern two-player implementation of the classic Space Invaders game built with Python and Pygame. Features enhanced gameplay mechanics, power-ups, and dynamic difficulty scaling.
## DEMO 
### Menu 
![image](https://github.com/user-attachments/assets/d755b54c-aeee-43ad-8a88-0fa59419b062)
### Ingame 
![image](https://github.com/user-attachments/assets/97a81057-ae5f-48ba-a1c6-830ecdace3ff)


## ✨ Features

### Game Mechanics
- Two-player cooperative gameplay
- Dynamic difficulty scaling based on score
- Enemy ships with unique attack patterns
- Boss enemy ships at score milestones
- Collision detection system
- Score tracking system
- Victory and defeat conditions

### Visual & Audio
- Custom sprites for all game elements
- Multiple enemy types with different designs
- Background music and sound effects
- Menu system with customizable options
- Animated explosions
- Retro-style visuals

### Special Features
- Sound toggle functionality
- Interactive menu system
- Score-based progression system
- Multiple bullet types
- Enemy ship special attacks

## 🛠️ Requirements

- Python 3.x
- Pygame
- Required libraries:
  - math
  - random
  - time
  - winsound (for Windows systems)

## 📦 Installation

1. Clone this repository
2. Install required packages:
```bash
pip install pygame
```
3. Ensure all assets are in the correct directory:
   - Images: .png files
   - Sounds: .wav files
   - Fonts: '8-BIT WONDER.ttf'

## 🎮 Controls

### Player 1:
- Left Arrow: Move left
- Right Arrow: Move right
- Spacebar: Shoot

### Player 2:
- A: Move left
- D: Move right
- E: Shoot

### General Controls:
- ESC: Pause game
- M: Toggle sound

## 🎯 Game Elements

### Players
- Two spaceships with individual controls
- Limited shooting rate
- Collision detection with enemy bullets

### Enemies
- Regular enemies with random movement patterns
- Boss ships appearing at score milestones
- Different enemy types with unique behaviors
- Progressive difficulty increase

### Power-ups
- Score-based power-up system
- Special enemy ships
- Speed modifications
- Point multipliers

## 📊 Scoring System

- Regular enemies: +1 point
- Special ships: +1 point
- Score milestones trigger new challenges:
  - Score 5: Increased enemy speed
  - Score 10: Additional enemies
  - Score 15: Boss appearance
  - Score 20: Maximum difficulty
  - Score 50: Victory condition

## 🎨 Assets Required

### Images
- player.png (Player 1 ship)
- player2.png (Player 2 ship)
- enemy.png, enemy1.png, enemy2.png (Enemy variations)
- bullet.png, bullet2.png (Player bullets)
- Ship_bullet1.png, Ship_bullet2.png, Ship_bullet3.png (Enemy bullets)
- background.png (Game background)
- menubackground.jpg (Menu background)
- galaxy.png (Game icon)

### Sound Files
- background.wav (Main game music)
- background2.wav (Menu music)
- shoot.wav, shoot1.wav (Shooting sounds)
- explosion.wav, explosion2.wav, explosion3.wav (Explosion effects)
- die.wav (Player defeat sound)
- levelup.wav (Level progression sound)
- error.wav (Error sound)
- transition.wav (Menu transition sound)

## 🔧 Technical Details

- Window Size: 800x600 pixels
- FPS-based animation system
- Dynamic difficulty scaling
- Multiple bullet patterns
- Collision detection using distance calculation
- Menu state management
- Sound management system

## 🚀 Getting Started

1. Run the game:
```bash
python main.py
```

2. Select options from the main menu:
   - Start Game
   - Toggle Sound
   - Exit

3. Play cooperatively to achieve the highest score possible!

## 💡 Tips

- Coordinate with your co-player to maximize coverage
- Watch for special enemy ships that appear at score milestones
- Use the sound toggle if you need to focus
- Keep track of both ships' positions to avoid friendly fire
- Work together to reach the victory condition at score 50

## 🤝 Contributing

Feel free to fork this project and submit pull requests. You can also open issues for bugs or feature suggestions.

## 📝 License

This project is open source and available under the MIT License.

## 🎮 Credits

Created by DuyMinh - A modern reimagining of the classic Space Invaders with multiplayer features and enhanced gameplay mechanics.
