# My Neovim Configuration

Welcome to my Neovim configuration repository! This repository contains my personal Neovim configuration, including settings, key mappings, plugins, and themes tailored to my preferences and workflow.

- I am using `Linux Ubuntu 22.04.4 LTS 6.5.0-27-generic` and `xterm-256color`

## Prerequisites

    - Neovim 0.6.0 or later
    - Ripgrep (rg) 11.0.2 or later
    - Lazygit 0.30.3 or later
    ```bash
        brew install jesseduffield/lazygit/lazygit
    ```

## Steps to use my config

1. Create a backup of your existing Neovim configuration (if you have one) by running the following command:
   ```bash
   mv ~/.config/nvim ~/.config/nvim.bak
   ```
2. Create a new Neovim configuration directory by running the following command:
   ```bash
   mkdir -p ~/.config/nvim
   ```
3. Clone this repository into the newly created Neovim configuration directory by running the following command:
   `bash
    git clone
    `
   and remove .git folder
   `bash
    rm -rf .git
    `
   (NOTE: I have used my name as the directory inside the lua folder, feel free to change it to your name or any other name you like. Just make sure to change `monal` in every file to the name you choose.)

4. Install the plugins by opening Neovim and running the following command:

   ```vim
   :Lazy
   ```

   and click I and U to install and update plugins

5. Restart Neovim to apply the changes.
