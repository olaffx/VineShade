# 🍷 VineShade
First shader software for Roblox on Linux!

Vineshade is a lightweight, ReShade-like launcher designed specifically for Sober (the x86_64 Roblox Android runtime). It's optimized to hit 240 FPS on NVIDIA hardware.

**Before running VineShade, please change the effect names in vkBasalt.conf file.**

# 🛠️ Installation

**1. Prerequisites**

Ensure you have vkBasalt installed on your system.

**For Arch Linux / Manjaro / EndeavourOS / Linexin**

`yay -S vkbasalt lib32-vkbasalt`

**For Linux Mint / Ubuntu / Debian / Pop_OS!**

`sudo apt install vkbasalt`

**For Fedora / Nobara**

`sudo dnf install vkbasalt`

**For openSUSE Tumbleweed**

`sudo zypper install vkbasalt`

**2. Effects**

Get any effects you want to use.

**Recommended effect repositories**

https://github.com/crosire/reshade-shaders

https://github.com/BlueSkyDefender/AstrayFX

**3. Adding the effects**

To make them recognizable, use this path:

`SHADERS_DIR="$HOME/reshade-shaders/Shaders"`
`TEXTURES_DIR="$HOME/reshade-shaders/Textures"`

**4. Making the launcher executable**

To make the main launcher open, please use this command in your terminal. This will make the launcher executable.

`chmod +x vineshade`

Once you have installed the prerequisites and set your effects, simply run the launcher from your terminal:

`./vineshade`

**4. Legal & Credits**

VineShade is an independent community project.

    Roblox is a registered trademark of Roblox Corporation. (https://roblox.com)

    Sober is developed by the VinegarHQ team. (https://github.com/vinegarhq)

    vkBasalt is an open-source Vulkan post-processing layer. (https://github.com/DadSchoorse/vkbasalt)
    
**This software is provided "as is" under the MIT License. Use at your own risk. VineShade is not responsible for any account bans or hardware issues, though it is designed with safety and stability as a priority.**

**5. FAQ**

**Does this work on AMD?**

Yes, VineShade works for every GPU.

**Does it work on every Linux distro?**

If you can install vkBasalt and Sober, yes you can use it in every distro.

**Will this get patched by Roblox?**

No, VineShade uses no injection methods.

**Is it safe?**

Yes, VineShade is 100% safe. You can inspect the code very easily.
