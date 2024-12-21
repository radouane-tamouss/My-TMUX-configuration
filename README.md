# TMUX Configuration

This is my customized `.tmux.conf` file. It's set up to make working with TMUX a breeze, especially if you're into web development or C/C++ development with Neovim.

## Why Use TMUX?

TMUX is awesome because it lets you manage multiple terminal sessions in one window. Here are some reasons to use it:

- **Persistent Sessions**: Your sessions stay alive even if you disconnect.
- **Multiple Panes**: Split your terminal into multiple panes for better multitasking.
- **Session Management**: Easily switch between different projects and tasks.
- **Customization**: You can tweak it to fit your workflow perfectly.

## What's in My Config?

1. **256 Colors Support**: Makes sure your terminal supports 256 colors for better visuals.
2. **Enable Faster Pane Switching**: Quickly switch between panes using `Ctrl+h`, `Ctrl+j`, `Ctrl+k`, and `Ctrl+l`.
3. **Improve Scrolling Performance**: Enhances the performance of scrolling within the terminal.
4. **Increase History Limit**: Increases the scrollback buffer to 10,000 lines.
5. **Enable Mouse Support**: Lets you interact with TMUX using the mouse.
6. **Status Bar Customization**: Reduces the frequency of status bar updates to 60 seconds.
7. **Disable Unnecessary Visual Effects**: Turns off visual activity, bell, and silence notifications.
8. **Additional Configurations for Neovim (LazyVim)**: 
   - Split window vertically and open Neovim with `v`.
   - Split window horizontally and open Neovim with `s`.
9. **Reload TMUX Configuration**: Reload the TMUX configuration with `r`.

## How to Use It

1. Clone the repository:
   ```sh
   git clone https://github.com/radouane-tamouss/My-TMUX-configuration
   ```

2. Copy the `.tmux.conf` file to your home directory:
   ```sh
   cp tmux-config/.tmux.conf ~/
   ```

3. Reload TMUX configuration:
   ```sh
   tmux source-file ~/.tmux.conf
   ```

