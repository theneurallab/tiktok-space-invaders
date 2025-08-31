# Space Invaders Game

A classic Space Invaders arcade game implementation using Python and Pygame with sound effects, scoring system, and multiple levels.

## Features

- Sound effects for shooting, explosions, and game over
- Progressive difficulty with increasing levels
- High score tracking
- Pause/resume functionality
- Audio mute/unmute controls

## Requirements

- Python 3.6+
- Pygame library

## Steps to Run this Codebase

1. Fork this repository: `https://github.com/theneurallab/tiktok-space-invaders.git`
2. Clone your forked repository (replace `YOUR_USERNAME` with your actual GitHub username):

```bash
git clone https://github.com/YOUR_USERNAME/tiktok-space-invaders.git
```

3. Navigate to the project directory:

```bash
cd tiktok-space-invaders
```

4. Install the required dependencies:

```bash
pip install -r requirements.txt
```

5. Run the game:

```bash
python main.py
```

6. A pygame window will open and the game will start with a welcome screen

## Game Controls:

- **Arrow Keys / A,D**: Move spaceship left/right
- **Space / S**: Fire bullets
- **P**: Pause/unpause game
- **M**: Mute/unmute audio
- **R**: Restart game (when game over)
- **Q**: Quit game (when game over)

## Project Structure

```
tiktok-space-invaders/
├── assets/
│   ├── audios/
│   │   ├── BulletFired.wav
│   │   ├── EnemyKilled.wav
│   │   └── PlayerDied.wav
│   └── images/
│       ├── background.png
│       ├── bullet.png
│       ├── enemy.png
│       ├── UFO.png
│       ├── Explosion.png
│       ├── Audio.png
│       ├── No Audio.png
│       ├── Keys1.png
│       ├── Keys2.png
│       └── icon.png
├── main.py                # Main game script
├── requirements.txt       # Python dependencies
├── data.json              # High score storage
└── README.md              # Project documentation
```

Made with ❤️ by [Neural Lab](https://theneurallab.com)
