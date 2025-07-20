# Alacritty Configuration

This repository contains my personal configuration for [Alacritty](https://github.com/alacritty/alacritty), a GPU-accelerated terminal emulator written in Rust.

## Structure

```
.
├── alacritty.toml    # Main configuration file
└── themes/           # Collection of color themes
    ├── catppuccin/   # Official Catppuccin themes from catppuccin/alacritty
    |  ├── catppuccin-frappe.toml
    |  ├── catppuccin-latte.toml
    |  ├── catppuccin-macchiato.toml
    |  └── catppuccin-mocha.toml
    |  # Other themes from alacritty/alacritty-theme
    ├── dracula.toml
    ├── gruvbox_dark.toml
    └── many more...
```

## Setup Instructions

1. **Install Alacritty**

    - On Ubuntu/Debian:
        ```bash
        sudo apt install alacritty
        ```
    - On Arch Linux:
        ```bash
        sudo pacman -S alacritty
        ```
    - For other distributions, please refer to the [official documentation](https://github.com/alacritty/alacritty#installation).

2. **Clone this repository**

    ```bash
    git clone https://github.com/sanghaarsha/alacritty-config.git ~/.config/alacritty
    ```

3. **Configuration Location**
    - The configuration files should be placed in:
        - Linux: `~/.config/alacritty/`
        - macOS: `~/.config/alacritty/`
        - Windows: `%APPDATA%\alacritty\`

## Theme Collection

This configuration includes a vast collection of carefully curated themes. Some notable themes include:

-   Dracula
-   Gruvbox (Light/Dark)
-   Nord
-   Catppuccin (All variants)
-   GitHub (Light/Dark)
-   Many more!

To change themes, modify the `import` section in your `alacritty.toml`:

```toml
general.import = [
    "~/.config/alacritty/themes/dracula.toml"  # Change this to your preferred theme
]
```

## Customization

The main configuration file `alacritty.toml` uses TOML format. You can customize various aspects of your terminal including:

-   Font configuration
-   Window settings
-   Cursor customization
-   Key bindings
-   Shell integration
-   And more!

For detailed configuration options, refer to the [Alacritty documentation](https://github.com/alacritty/alacritty/blob/master/docs/configuration.md).
