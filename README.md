# .dotfiles

Welcome to my dotfiles repository! This is where I store and manage the configuration files and settings I use to customize my development environment.

## Features

- **Neovim Configuration**

  - Includes a personalized setup with plugins and a black status line.
  - Optimized for productivity and minimal distractions.

- **WezTerm Configuration**

  - Tailored terminal emulator settings for better aesthetics and performance.

- **macOS Optimization**
  - Configurations and scripts specifically designed for macOS.

## Structure

```plaintext
.dotfiles/
├── nvim/               # Neovim configuration files
├── wezterm/            # WezTerm configuration files
├── zsh/                # Zsh shell configuration
├── scripts/            # Custom scripts for automation
├── git/                # Git configuration files
└── README.md           # Documentation for the repository
```

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/ajaxecho3/.dotfiles.git ~/.dotfiles
   ```

2. Navigate to the `.dotfiles` directory:

   ```bash
   cd ~/.dotfiles
   ```

3. Run the setup script to symlink configuration files:
   ```bash
   ./install.sh
   ```

## Usage

- Customize each configuration file according to your needs.
- Use `git` to track changes and sync across machines.
- Update submodules (if any):
  ```bash
  git submodule update --init --recursive
  ```

## Contribution

Feel free to fork this repository and submit a pull request if you have any improvements or suggestions!

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- Inspired by various dotfiles repositories from the open-source community.
- Special thanks to the developers of Neovim, WezTerm, and other tools featured in this repository.

---

Happy hacking! 🎉
