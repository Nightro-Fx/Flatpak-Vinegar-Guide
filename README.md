<body>
    <h1 align="center">
        <img src="https://github.com/Nightro-Fx/Flatpak-Vinegar-Guide/blob/main/image.png" width="40" alt="Logo"/> 
        Flatpak Vinegar Studio Guide
    </h1>
</html>

#### ❤️ Acknowledgements  
Massive shoutout to the [Official Vinegar Discord Server](https://discord.gg/vinegarhq-1069506340973707304) for providing me the resources and the information needed to make this guide possible.

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
##### Adding Models to Roblox Studio
```
flatpak override --user --filesystem=home org.vinegarhq.Vinegar
```

##### Configuring Vinegar
```
```


##### Configuration of Vinegar
```
[studio]
renderer = "Vulkan"
```
>[!IMPORTANT]
> Refer to the Official Vinegar Documentation for Configuration Details:
> [Vinegar Configuration Guide](https://vinegarhq.org/Configuration/)

##### Adding FastFlags To Studio
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
