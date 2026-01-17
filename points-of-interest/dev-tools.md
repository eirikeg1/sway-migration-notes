# Dev tools

## Alacritty
* Use alacritty from fotfiles
  * Requires to install nerd fonts, which is shown below:

```bash
# Create a directory for local fonts
mkdir -p ~/.local/share/fonts

# Download the JetBrainsMono Nerd Font zip
wget -P /tmp https://github.com/ryanoasis/nerd-fonts/releases/latest/download/JetBrainsMono.zip

# Unzip directly into your fonts directory
unzip -o /tmp/JetBrainsMono.zip -d ~/.local/share/fonts

# Refresh the font cache so the system sees it
fc-cache -fv


# Clean up
rm /tmp/JetBrainsMono.zip
```
