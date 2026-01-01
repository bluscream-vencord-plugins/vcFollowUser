# FollowUser

Adds a follow option in the user context menu to always be in the same VC as them.

![Screenshot](./screenshot.png)

## Features

- Follow a user to automatically join the same voice channel as them
- Automatically leave when the followed user leaves (optional)
- Auto-move back if you get moved while following
- Manual trigger option for more control
- Visual indicator in the toolbar showing who you're following

## Installation

1. Enable the plugin in Vencord's settings
2. Right-click a user and select "Follow User" from the context menu

## Configuration

- **Execute On Follow**: Make sure to be in the same VC when following a user (default: true)
- **Only Manual Trigger**: Only trigger on indicator click (default: false)
- **Follow Leave**: Also leave when the followed user leaves (default: false)
- **Auto Move Back**: Automatically move back to the VC of the followed user when you get moved (default: false)
- **Channel Full**: Attempt to move you to the channel when it's not full anymore (default: true)

## Usage

Right-click any user and select "Follow User" from the context menu. The plugin will automatically join the same voice channel as them whenever they move. A follow indicator will appear in the toolbar - click it to manually trigger a follow action, or right-click it to unfollow.

## AI Disclaimer

This plugin was developed with assistance from **Cursor.AI** (Cursor's AI coding assistant). The AI was used to help with code generation, debugging, documentation, and implementation. While AI assistance was utilized, all code and features were reviewed and tested to ensure quality and functionality.

## License

GPL-3.0-or-later
