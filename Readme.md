
# Create a new file (we take example Telegram)
nano ~/.local/share/applications/telegram.desktop

# Copy and paste the script (Modifie your app name)

chmod +x ~/.local/share/applications/telegram.desktop

# You can add icon
Icon=/home/faker/Downloads/Telegram/telegram.png

# Refresh Apps Menus
sudo update-desktop-database ~/.local/share/applications
