Gemini's Roguelike

Welcome to Gemini's Roguelike: The Princess's Last Hope! This is an isometric dungeon-crawling adventure game developed using Pygame. Embark on a perilous journey through dangerous dungeons, battle fearsome monsters, and solve puzzles to rescue the kidnapped princess from the clutches of evil.

✨ Features

    Isometric Graphics: Explore a visually distinct dungeon environment.

    Procedural Level Generation: Each playthrough offers a new map layout.

    Character Progression: Level up your hero, gain new abilities, and find powerful equipment.

    Tactical Combat: Engage in turn-based battles against a variety of monsters.

    Inventory & Equipment System: Manage your gear and adapt to dungeon challenges.

    Field of View & Lighting: Dynamic lighting system adds to the atmospheric exploration.

    Boss Battles: Face off against unique and challenging bosses at the end of each level.

    Dialogue System: Interact with characters and unravel the story.

    Background Music: Immerse yourself in the adventure with captivating background music.

🚀 Installation

To run Gemini's Roguelike, you'll need Python 3 and a few libraries.

Prerequisites
  Python 3.x
  
  pygame
  
  moviepy (for the victory video, though it's optional if you remove the video playback code)

Steps
  Clone the Repository:
  
  git clone https://github.com/TotalCranberry/Geminis-Rougelike.git
  cd Geminis-Rougelike
  
  Install Dependencies:
  
  pip install pygame moviepy
  
  Prepare Assets:
  Ensure you have an assets folder in the root directory of the project, containing all the necessary image and audio files as referenced in game.py.
  
  player.png, goblin.png, slime.png, bat.png, skeleton.png, potion.png, chest.png, floor.png, wall.png, stairs.png, barrel.png, crate.png, torch.png,   sword.png, shield.png, armor.png, staff.png, inventory_slot.png, fireball.png, arrow.png, bow.png, gargoyle.png, fenrir.png, chimera.png, hydra.png, dragon.png, princess.png, key.png, door.png, menu.png.
  
  victory.mov (optional, for the victory video playback).
  
  bg_music.mp3 (or .ogg, for background music).
  
  Run the Game:
  
  python game.py

🎮 How to Play
  Controls:
  Movement: Arrow Keys or HJKL
  
  Pick Up Item: G
  
  Use/Equip Item: 1 - 9 (corresponding to inventory slots)
  
  Descend Stairs: .  (Period)
  
  Use Magic/Ranged (Targeting Mode): F
  
  Move Target: Arrow Keys
  
  Confirm Target: Enter
  
  Cancel Targeting: Escape
  
  Toggle Help Menu: / (Slash)
  
  Quit Game (from Menu/Game Over): ESC
  
  Restart Game (from Game Over/Victory): R

Objective:
Navigate through multiple dungeon levels, defeat the level boss to reveal the stairs, and ultimately confront the dragon on the final level to rescue the princess! Explore the map to find keys, unlock doors, and uncover hidden items.

🎨 Assets
All game sprites and sound files are expected to be located in the assets/ directory. If any asset files are missing, the game may display a placeholder or encounter errors.

🤝 Contributing
Contributions are welcome! If you have suggestions for improvements, bug fixes, or new features, please feel free to:

Fork the repository.

Create a new branch (git checkout -b feature/your-feature-name).

Make your changes.

Commit your changes (git commit -m 'Add new feature').

Push to the branch (git push origin feature/your-feature-name).

Open a Pull Request.

📜 License
This project is open-source and available under the MIT License.

✉️ Contact
For any questions or feedback, please open an issue on the GitHub repository.

