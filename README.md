# Arch Linux Configuration Files

Personal configuration files for my Arch Linux setup, including window managers, development tools, and system utilities.

![image](https://github.com/user-attachments/assets/32670f23-2861-4352-9df6-8afddc6bfc65)
![image](https://github.com/user-attachments/assets/f97c30cb-e9cd-42af-b133-9ad8460d8879)
![image](https://github.com/user-attachments/assets/b93af6c2-3e1e-43f7-be4d-fc767f669c39)
![image](https://github.com/user-attachments/assets/17c26e81-d1f9-4618-895d-77d3167ce164)



## Configuration Components

### Window Manager & Desktop
- **Hyprland**: Wayland compositor settings
- **Waybar**: Highly customizable status bar
- **Waypaper**: Wallpaper manager for Wayland
- **Rofi**: Application launcher and window switcher

### Development Environment
- **Neovim**: Text editor configuration
- **Zed**: Modern code editor settings
- **Lazygit**: Terminal UI for git
- **Github Copilot**: AI pair programming configuration
- **Go**: Go language configuration

### Terminal Utilities
- **Kitty**: Modern terminal emulator
- **Tmux**: Terminal multiplexer with powerline
- **Btop**: System monitor configuration
- **Htop**: Process viewer settings
- **Fastfetch**: System information tool
- **Thefuck**: Command correction tool

### File Management
- **Ranger**: File manager configuration
- **Dolphin**: KDE file manager settings
- **Nautilus**: GNOME file manager preferences
- **Baloo**: File indexing configuration
  - `baloofilerc`
  - `baloofileinformationrc`

### Media & Documents
- **VLC**: Media player configuration
- **Ncspot**: Spotify TUI client
- **Zathura**: PDF viewer settings
- **Wal**: Color scheme generator

### System Configuration
- **GTK-3.0**: GTK theme settings
- **Qt Project**: Qt application settings
- **Pulse**: Audio configuration
- **IBus**: Input method framework
- **dconf**: GNOME system settings

## Installation

1. Clone the repository:
```bash
git clone https://github.com/dantealegria1/.config.git ~/.config
```

2. Install required packages:
```bash
yay -S hyprland waybar waypaper rofi neovim zed lazygit github-copilot kitty tmux btop htop fastfetch thefuck ranger dolphin nautilus vlc ncspot zathura python-pywal
```

## Directory Structure

```bash
.config/
├── hypr/               # Hyprland compositor config
├── waybar/             # Status bar configuration
├── waypaper/           # Wallpaper manager settings
├── rofi/               # Application launcher config
├── nvim/               # Neovim configuration
├── zed/                # Zed editor settings
├── kitty/              # Kitty terminal config
├── tmux/               # Tmux configuration
├── tmux-powerline/     # Tmux powerline theme
├── btop/               # System monitor config
├── ranger/             # File manager settings
├── ncspot/             # Terminal Spotify client
└── wal/                # Color scheme settings
```

## Key Features

### Hyprland Setup
- Modern Wayland compositor
- Custom animations and effects
- Multi-monitor support
- Integration with Waybar

### Development Tools
- Neovim with custom plugins
- Zed editor configuration
- Lazygit integration
- Github Copilot setup

### Terminal Experience
- Kitty with custom settings
- Tmux with powerline theme
- Advanced system monitoring (btop/htop)
- Command-line productivity tools

## Dependencies

Essential packages can be installed via pacman/yay:
```bash
# Core components
yay -S hyprland waybar waypaper rofi

# Development tools
yay -S neovim zed lazygit github-copilot-cli

# Terminal utilities
yay -S kitty tmux btop htop fastfetch thefuck

# File management
yay -S ranger dolphin nautilus

# Media tools
yay -S vlc ncspot zathura python-pywal
```

## Customization

Configuration files can be modified in their respective directories:

- Hyprland: `~/.config/hypr/`
- Waybar: `~/.config/waybar/`
- Neovim: `~/.config/nvim/`
- Kitty: `~/.config/kitty/`
- Tmux: `~/.config/tmux/`

## Repository

[https://github.com/dantealegria1/.config](https://github.com/dantealegria1/.config)

## License

This project is open source and available for personal use.

## Contact

- GitHub: [@dantealegria1](https://github.com/dantealegria1)
