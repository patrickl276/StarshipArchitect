# **Assets Directory**

This directory contains all the game assets used in **Starship Architect**, including images, sounds, fonts, and more. The assets are organized into subfolders based on their type and use within the game. This structure helps keep the project organized and ensures that all assets are easy to find and manage.

## **Directory Structure**

'''plaintext
/assets
│
├── /images # All game-related images
│ ├── /ui # Images for UI elements like buttons, icons, etc.
│ ├── /sprites # Sprites for game characters and animations
│ │ ├── /characters # Sprites for all characters (crew members, NPCs)
│ │ ├── /modules # Sprites for different ship modules (habitats, reactors, etc.)
│ │ └── /effects # Visual effects like explosions, animations, etc.
│ ├── /backgrounds # Background images for various game scenes
│ └── /misc # Miscellaneous images (logos, placeholders, etc.)
│
├── /sounds # Sound files for the game
│ ├── /music # Background music tracks
│ ├── /effects # Sound effects (button clicks, alarms, etc.)
│ └── /voice # Voice lines or character sounds
│
├── /fonts # Custom fonts used throughout the game
│
├── /videos # Cutscenes or animations (if we use any)
│
├── /data # Data files for game configuration
│ ├── /json # JSON files for game data and settings
│ └── /xml # XML files for configuration and settings
│
└── /shaders # Shaders for advanced graphical effects
'''

## **Folder Descriptions**

- **/images**: Contains all image assets used in the game.

  - **/ui**: UI elements like buttons, icons, and backgrounds.
  - **/sprites**: Game sprites and animations.
    - **/characters**: Sprites for all game characters (crew members, NPCs).
    - **/modules**: Sprites representing different ship modules.
    - **/effects**: Visual effects such as explosions or animations.
  - **/backgrounds**: Background images for various game scenes.
  - **/misc**: Miscellaneous images, such as logos or placeholders.

- **/sounds**: Contains all sound files.

  - **/music**: Background music tracks for different game environments.
  - **/effects**: Sound effects used in the game.
  - **/voice**: Voice lines or sounds associated with characters or announcements.

- **/fonts**: Custom fonts used throughout the game to maintain a consistent style.

- **/videos**: Contains any video files used in the game, such as cutscenes or animations.

- **/data**: Data files used for configuration and game content.

  - **/json**: JSON files for game configuration and structured data.
  - **/xml**: XML files for game configuration and structured data.

- **/shaders**: Contains shader programs for special graphical effects.

## **Naming Conventions**

- Use clear, descriptive names for all files. For example:
  - **UI Elements**: `btn_play.png`, `icon_settings.png`
  - **Sprites**: `crew_member_idle.png`, `ship_module_reactor.png`
  - **Sound Effects**: `click_button.wav`, `alarm_warning.mp3`
  - **Background Music**: `ambient_space.mp3`

## **Optimization Guidelines**

- **Image Optimization**: Compress images to reduce file size without sacrificing quality.
- **Sound Compression**: Use compressed audio formats like MP3 or OGG for sound effects and music to minimize file size.
- **Version Control**: Commit only optimized and final assets to avoid repository bloat.

## **Contributing to the Assets Folder**

1. **Add New Assets**: Place new assets in the appropriate subfolder and follow naming conventions.
2. **Update Assets**: When updating existing assets, ensure the updated file maintains the same name unless a significant version change requires a new name.
3. **Delete Unused Assets**: Remove any unused assets to keep the folder clean and efficient.

## **Contact**

For any questions or suggestions regarding asset management, please contact patricklong010@gmail.com.
