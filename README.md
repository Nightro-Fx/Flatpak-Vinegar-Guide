<body>
    <h1 align="center">
        <img src="https://github.com/Nightro-Fx/Flatpak-Vinegar-Guide/blob/main/image.png" width="40" alt="Logo"/> 
        Flatpak Vinegar Studio Guide
    </h1>
</html>

#### ❤️ Acknowledgements  
Massive shoutout to the [Official Vinegar Discord Server](https://discord.gg/vinegarhq-1069506340973707304) for providing me the resources and the information needed to make this guide possible.

###### Installing Roblox Studio from Flatpak
```bash
sudo apt update
sudo apt upgrade -y
sudo apt install gnome-software -y
sudo apt install flatpak -y
sudo apt install flatpak gnome-software-plugin-flatpak -y
flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
flatpak install flathub org.vinegarhq.Vinegar -y
flatpak run org.vinegarhq.Vinegar
```
