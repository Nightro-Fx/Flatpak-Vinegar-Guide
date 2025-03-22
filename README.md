<body>
    <h1 align="center">
        <img src="https://github.com/Nightro-Fx/Flatpak-Vinegar-Guide/blob/main/img/Flathub.png" width="40" alt="Logo"/> 
        Flatpak Vinegar Studio Guide
    </h1>
</html>

#### ❤️ Acknowledgements  
Thank you [VinegarHQ](https://vinegarhq.org/) for making this guide possible. Further support will be provided over my support server, [Here](https://discord.gg/kNHaaFsGZ2).

##### Installing Roblox Studio from Flatpak
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
##### Adding 3D Models to Roblox Studio
```
flatpak override --user --filesystem=home org.vinegarhq.Vinegar
```
>[!TIP]
> By default, Your C-Drive named *drive_c* is located at `~/.var/app/org.vinegarhq.Vinegar/data/vinegar/prefixes/studio`, where you can copy your models to.

##### Configuring Vinegar
<img src="https://github.com/Nightro-Fx/Flatpak-Vinegar-Guide/blob/main/img/MainMenu.png" width="300" alt="Logo"/> <img src="https://github.com/Nightro-Fx/Flatpak-Vinegar-Guide/blob/main/img/ConfigMenu.png" width="300" alt="Logo"/> 

##### Configuration of Vinegar
```
[studio]
renderer = "Vulkan"
```
>[!IMPORTANT]
> Refer to the Official Vinegar Documentation for Configuration Details:
> [Vinegar Configuration Guide](https://vinegarhq.org/Configuration/)

##### Adding Performance FastFlags To Studio (Optional)
```
[studio.fflags]
DFIntTaskSchedulerTargetFps = 120
FIntRenderShadowIntensity = 0
FIntRenderLocalLightUpdatesMax = 8
FIntRenderLocalLightUpdatesMin = 4
DFIntPerformanceControlTextureQualityBestUtility = -1
FIntFRMMinGrassDistance = 0  
FIntFRMMaxGrassDistance = 0  
FIntRenderGrassDetailStrands = 0  
FIntRenderGrassHeightScaler = 0  
DFIntDebugFRMQualityLevelOverride = 1
FFlagGlobalWindRendering = False  
FFlagGlobalWindActivated = False  
```
