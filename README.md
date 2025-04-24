# Spotify to UwuFufu Automation Tool

A Python automation tool that gets tracks from a Spotify playlist, finds their corresponding YouTube videos, and automatically uploads them to a UwuFufu quiz game.

## Features

- Extracts tracks from any public Spotify playlist
- Automatically searches YouTube for each track to find matching videos
- Creates a new UwuFufu game
- Automatically adds all YouTube videos to the game
- Outputs a text file with all track-YouTube mappings

## Requirements

- Python 3.6+
- Chrome browser installed
- Internet connection

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/spotify-uwufufu-automation.git
   cd spotify-uwufufu-automation
   ```

2. Install the required Python packages:
   ```
   pip install selenium requests
   ```

3. Make sure you have the Chrome browser installed on your system.

## Usage

1. Run the script:
   ```
   python auto_uwu.py
   ```

2. When prompted, enter the following information:
   - Your Spotify playlist URL (must be public)
   - Your UwuFufu email and password
   - The title and description for your new UwuFufu game

3. The script will then:
   - Extract tracks from the Spotify playlist
   - Search YouTube for each track
   - Log in to UwuFufu
   - Create a new game
   - Add all the YouTube videos automatically
  
4. Feel free to test out different sleep times between operations to see if it can be automated faster

5. Once complete, you'll see the UwuFufu game editor with all your videos added. You can then review and publish your game.

## Output

The script generates a file called `spotify_to_youtube.txt` which contains a mapping of all tracks to their found YouTube URLs.

## Troubleshooting

- **Videos not being added**: If the script is failing to add videos, try reducing the number of videos or check if the UwuFufu interface has changed.
- **Login issues**: Make sure your UwuFufu credentials are correct.
- **Spotify playlist not loading**: Make sure your Spotify playlist is public and the URL is correct.
